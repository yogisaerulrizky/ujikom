<template>
  <nav class="navbar navbar-expand-lg bg-body-tertiary">
    <div class="container-fluid">
      <a class="navbar-brand" href="/">Home</a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link" aria-current="page" href="/eskul/"
              >Ekstrakulikuler</a
            >
          </li>
          <div class="dropdown">
            <button
              class="btn btn-secondary dropdown-toggle"
              type="button"
              data-bs-toggle="dropdown"
              aria-expanded="false"
            >
              profile
            </button>
            <ul class="dropdown-menu">
              <li><NuxtLink to="/profil/visimisi" class="dropdown-item">visi & misi</NuxtLink></li>
              <li><a class="dropdown-item" href="/profil/sejarah">sejarah</a></li>
            </ul>
          </div>
          <li class="nav-item">
            <a class="nav-link" href="/gallery/">gallery</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="/Tentangkami/">Tentangkami</a>
          </li>
          
            <li class="nav-item">
              <a class="nav-link" href="/Biodata/">Biodata</a>
          </li>
          
        </ul>
      </div>
    </div>
  </nav>
</template>