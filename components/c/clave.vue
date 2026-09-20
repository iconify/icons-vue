<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ma3uu5i5k"/><path class="p9rfrybpk"/><path class="k9pd4oeha"/><path class="p1uu2abrr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:clave" /></template>
<style>
.bi12bsetm {
  fill: none;
  fill-rule: evenodd;
}

.k9pd4oeha {
  fill: var(--svg-color--00ced1, #00ced1);
  d: path("M18.543 18.519c-.665 1.18-2.135 1.583-3.286.902l-8.925-5.285c-1.15-.681-1.545-2.19-.88-3.37c.663-1.179 2.134-1.583 3.284-.902l8.926 5.285c1.15.681 1.545 2.19.88 3.37");
}

.ma3uu5i5k {
  fill: var(--svg-color--0795b0, #0795b0);
  d: path("M18.549 5.482c-.665-1.18-2.135-1.584-3.285-.903L6.338 9.864c-1.15.681-1.545 2.19-.88 3.37c.663 1.179 2.134 1.583 3.285.902l8.925-5.285c1.15-.681 1.545-2.19.88-3.37");
}

.p1uu2abrr {
  fill: var(--svg-color--00e7eb, #00e7eb);
  d: path("M8.117 10.942a1.154 1.154 0 0 0-1.6.444c-.331.59-.13 1.34.433 1.672l8.926 5.285a1.154 1.154 0 0 0 1.6-.444c.332-.59.13-1.339-.433-1.672zm-3.733-.794c1-1.777 3.226-2.395 4.971-1.362l8.926 5.286l-.619 1.077l.62-1.077c1.737 1.029 2.323 3.296 1.327 5.066c-1 1.776-3.226 2.394-4.97 1.36l-8.927-5.284c-1.737-1.03-2.323-3.297-1.328-5.066");
}

.p9rfrybpk {
  fill: var(--svg-color--08adcc, #08adcc);
  d: path("M14.645 3.501c1.745-1.033 3.97-.415 4.97 1.362l-1.066.619l1.067-.62c.995 1.77.41 4.037-1.328 5.066l-8.926 5.286c-1.745 1.033-3.971.415-4.971-1.362c-.996-1.769-.41-4.037 1.328-5.066zm2.837 2.6a1.154 1.154 0 0 0-1.6-.444l-8.925 5.285l-.607-1.057l.607 1.057a1.243 1.243 0 0 0-.433 1.672a1.154 1.154 0 0 0 1.6.444l8.925-5.285a1.243 1.243 0 0 0 .433-1.672l1.052-.61z");
}

</style>
