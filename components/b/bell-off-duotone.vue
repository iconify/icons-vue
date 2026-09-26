<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qi9ptyb9c"/><path class="k0efr-bef"/><path class="ayo73pbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bell-off-duotone" /></template>
<style>
.ayo73pbzj {
  d: path("M2 2L22 22");
}

.k0efr-bef {
  stroke-opacity: 0.4;
  d: path("M10.2679 20C10.6252 20.6188 11.2855 21 12 21C12.7145 21 13.3748 20.6188 13.7321 20");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qi9ptyb9c {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 17H6C4.8954 17 4 16.1046 4 15C4 14.4387 4.2784 13.9674 4.455 13.673C4.6689 13.3166 4.8785 13.007 5.1056 12.5528C5.5331 11.6977 6 10.3517 6 8C6 7.3938 6.0899 6.8086 6.2571 6.2571L17 17ZM8.6837 4.441C8.4671 4.2245 8.3618 3.9206 8.3977 3.6165C8.4337 3.3124 8.607 3.0415 8.8681 2.8814C9.7797 2.3223 10.8522 2 12 2C15.3137 2 18 4.6863 18 8C18 8.9863 18.0943 9.7904 18.219 10.4532C18.2986 10.876 18.3961 11.2422 18.5032 11.5639C18.6518 12.0101 18.4741 12.4998 18.074 12.747C17.6739 12.9942 17.1564 12.9338 16.8239 12.6013L8.6837 4.441Z");
  stroke: none;
}

</style>
