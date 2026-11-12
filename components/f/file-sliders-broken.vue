<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e0cmz0boh"/><path class="t4qaumccy"/><path class="u_p8_wgxf"/><path class="y5olns9mo"/><path class="b22-7qb1v"/><path class="a8zd5hbca"/><path class="t9kq6vbei"/><path class="tlh989bna"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-sliders-broken" /></template>
<style>
.a8zd5hbca {
  d: path("M9.39062 17.2657L13.245 17.2656");
}

.b22-7qb1v {
  d: path("M11.4102 13.2188C11.4102 13.8918 10.8645 14.4375 10.1914 14.4375C9.51831 14.4375 8.97266 13.8918 8.97266 13.2188C8.97266 12.5457 9.51831 12 10.1914 12C10.8645 12 11.4102 12.5457 11.4102 13.2188Z");
}

.e0cmz0boh {
  d: path("M13 2.2627V5.0003C13 7.35732 13 8.53583 13.7322 9.26806C14.4645 10.0003 15.643 10.0003 18 10.0003H21.58");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t4qaumccy {
  stroke-linejoin: round;
  d: path("M2 10V14C2 17.7712 2 19.6569 3.17157 20.8284C4.34315 22 6.22876 22 10 22H14C17.7712 22 19.6569 22 20.8284 20.8284C21.4816 20.1752 21.7706 19.3001 21.8985 18M22 14V13.5629C22 11.8083 22 10.931 21.654 10.1541C21.308 9.3772 20.6559 8.79032 19.3517 7.61654L15.3929 4.05365C14.2651 3.03857 13.7012 2.53104 13.0092 2.26552C12.3173 2 11.5548 2 10.0298 2C6.23869 2 4.34315 2 3.17157 3.17157C2.51839 3.82475 2.22937 4.69989 2.10149 6");
}

.t9kq6vbei {
  d: path("M5.11914 17.2656L6.95312 17.2656");
}

.tlh989bna {
  d: path("M6.95313 17.2656C6.95313 16.5925 7.49878 16.0469 8.17188 16.0469C8.84497 16.0469 9.39063 16.5925 9.39063 17.2656C9.39063 17.9387 8.84497 18.4844 8.17188 18.4844C7.49878 18.4844 6.95313 17.9387 6.95313 17.2656Z");
}

.u_p8_wgxf {
  d: path("M8.97266 13.2186L5.1183 13.2187");
}

.y5olns9mo {
  d: path("M13.2441 13.2188L11.4102 13.2187");
}

</style>
