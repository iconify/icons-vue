<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-puvwbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bar-mat" /></template>
<style>
.w-puvwbcu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.83 3.25h9.905q1.761 0 2.769 1.444q1.007 1.444.399 3.097l-1.566 4.25q-.813 2.209-3.167 2.209H6.265q-1.761 0-2.769-1.444q-1.007-1.444-.399-3.097l1.566-4.25Q5.476 3.25 7.83 3.25M9.731 6Q8.259 6 7.67 7.348L7.188 8.45q-.472 1.079.173 2.064q.644.986 1.822.986h5.836q1.472 0 2.061-1.348l.482-1.102q.472-1.079-.173-2.064Q16.745 6 15.567 6zM21.25 19.75q0-1.326-1.914-3.719q-.052-.065-.117-.117q-.058-.046-.124-.08q-.065-.034-.136-.054q-.071-.021-.145-.027q-.073-.007-.147.002q-.073.008-.144.03t-.135.058t-.121.083t-.103.105q-1.914 2.393-1.914 3.719q0 2.5 2.5 2.5t2.5-2.5");
}

</style>
