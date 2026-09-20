<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="l3d92ib5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:android-logo-thin" /></template>
<style>
.l3d92ib5q {
  fill: currentColor;
  d: path("M172 148a8 8 0 1 1-8-8a8 8 0 0 1 8 8m-80-8a8 8 0 1 0 8 8a8 8 0 0 0-8-8m144 20v24a12 12 0 0 1-12 12H32a12 12 0 0 1-12-12v-22.87a109.43 109.43 0 0 1 37.18-82.29l-28-28a4 4 0 0 1 5.66-5.66l28.57 28.57A106.63 106.63 0 0 1 127.62 52h.38a107.16 107.16 0 0 1 64.78 21.57l28.39-28.4a4 4 0 1 1 5.66 5.66L199 78.64c1.78 1.56 3.52 3.17 5.21 4.86A107.25 107.25 0 0 1 236 160m-8 0A100 100 0 0 0 128 60h-.35C72.7 60.19 28 105.56 28 161.13V184a4 4 0 0 0 4 4h192a4 4 0 0 0 4-4Z");
}

</style>
