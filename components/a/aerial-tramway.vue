<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="z3p269btt"><path class="a8_riqb9l"/><path class="g3lijcc3z"/></g><path class="k0tqv4bzi"/><path class="u4h3w2b3d"/><path class="te3_lxn0t"/><path class="g7bod07yi"/><path class="grs_n-bii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:aerial-tramway" /></template>
<style>
.a8_riqb9l {
  d: path("M30 11.5h4v12h-4z");
}

.g3lijcc3z {
  d: path("M39.6 13L23.9 9.9l.5-2.9l3.5.7l3-2.5l3.9.7l2.1 3.5l3.2.6z");
}

.g7bod07yi {
  fill: var(--svg-color--dae3ea, #dae3ea);
  d: path("M55 49c0 5.5-4.5 10-10 10H19c-5.5 0-10-4.5-10-10z");
}

.grs_n-bii {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M24.8 46.9h-2.7c0-11.8 4-24 4-24h2.7c0-.1-4 12.2-4 24m14.4 0h2.7c0-11.8-4-24-4-24h-2.7c0-.1 4 12.2 4 24M54.1 53c.3-.6.5-1.3.6-2H9.2c.1.7.4 1.4.6 2z");
}

.k0tqv4bzi {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M62 19.1L2 7V5l60 12z");
}

.te3_lxn0t {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M51 44.9H13V33.4c0-4.6 3.7-8.3 8.3-8.3h21.4c4.6 0 8.3 3.7 8.3 8.3z");
}

.u4h3w2b3d {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M55 49H9V31.5c0-5.5 4.5-10 10-10h26c5.5 0 10 4.5 10 10z");
}

.z3p269btt {
  fill: var(--svg-color--94989b, #94989b);
}

</style>
