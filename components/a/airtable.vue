<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":215};
const content = `<path class="tb-15aczl"/><path class="aaz4chbua"/><path class="s9u1ygwmc"/><path class="wisqdmb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:airtable" /></template>
<style>
.aaz4chbua {
  fill: var(--svg-color--26b5f8, #26b5f8);
  d: path("M136.35 112.757v94.902c0 4.514 4.55 7.605 8.746 5.942l106.748-41.435a6.39 6.39 0 0 0 4.035-5.941V71.322c0-4.514-4.551-7.604-8.747-5.941l-106.748 41.434a6.39 6.39 0 0 0-4.035 5.942");
}

.s9u1ygwmc {
  fill: var(--svg-color--ed3049, #ed3049);
  d: path("m111.423 117.654l-31.68 15.296l-3.217 1.555L9.65 166.548C5.411 168.593 0 165.504 0 160.795V71.72c0-1.704.874-3.175 2.046-4.283a7.3 7.3 0 0 1 1.618-1.213c1.598-.959 3.878-1.215 5.816-.448l101.41 40.18c5.155 2.045 5.56 9.268.533 11.697");
}

.tb-15aczl {
  fill: var(--svg-color--ffbf00, #ffbf00);
  d: path("M114.259 2.701L18.86 42.176c-5.305 2.195-5.25 9.73.089 11.847l95.797 37.989a35.54 35.54 0 0 0 26.208 0l95.799-37.99c5.337-2.115 5.393-9.65.086-11.846L141.442 2.7a35.55 35.55 0 0 0-27.183 0");
}

.wisqdmb4y {
  fill-opacity: var(--svg-fill-opacity--0-25, 0.25);
  d: path("m111.423 117.654l-31.68 15.296L2.045 67.438a7.3 7.3 0 0 1 1.618-1.213c1.598-.959 3.878-1.215 5.816-.448l101.41 40.18c5.155 2.045 5.56 9.268.533 11.697");
}

</style>
