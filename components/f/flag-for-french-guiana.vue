<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="k6jyc5n0r"/><path class="zyd79gbbl"/><path class="ncmsnz9ej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-french-guiana" /></template>
<style>
.k6jyc5n0r {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("M2 32c0 16.6 13.4 30 30 30c11.7 0 21.9-6.8 26.8-16.6L5.2 18.6C3.1 22.6 2 27.2 2 32");
}

.ncmsnz9ej {
  fill: var(--svg-color--da121a, #da121a);
  d: path("M32 17.9L35.3 28h10.6l-8.6 6.3l3.3 10.1l-8.6-6.2l-8.6 6.2l3.3-10.1l-8.6-6.3h10.6z");
}

.zyd79gbbl {
  fill: var(--svg-color--699635, #699635);
  d: path("M32 2C20.3 2 10.1 8.8 5.2 18.6l53.7 26.8c2-4 3.2-8.6 3.2-13.4C62 15.4 48.6 2 32 2");
}

</style>
