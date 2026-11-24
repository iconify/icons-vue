<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="wgtm6ci6u"/><path class="ilvx_6zte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:duckdb-icon" /></template>
<style>
.ilvx_6zte {
  fill: var(--svg-color--fff100, #fff100);
  d: path("M97.308 75.054c-29.091 0-52.945 23.855-52.945 52.946c0 29.382 23.854 52.946 52.945 52.946c29.09 0 52.945-23.855 52.945-52.946S126.4 75.054 97.308 75.054m114.323 53.454l.007-.508c0-10.524-8.532-19.055-19.055-19.055H167.42v38.11h25.163c10.354 0 18.779-8.258 19.048-18.547");
}

.wgtm6ci6u {
  fill: var(--svg-color--1a1a1a, #1a1a1a);
  d: path("M128 256C57.31 256 0 198.691 0 128C0 57.31 57.018 0 128 0s128 57.31 128 128c0 70.691-57.309 128-128 128");
}

</style>
