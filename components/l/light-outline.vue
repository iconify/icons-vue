<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7x9o27hx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:light-outline" /></template>
<style>
.b7x9o27hx {
  fill: currentColor;
  d: path("M9.82 18.18q-.897-.896-.897-2.18H5q-.413 0-.706-.294T4 15q0-3.134 2.166-5.47T11.5 7.012V4.385h1v2.627q3.17.182 5.335 2.518T20 15q0 .413-.294.706T19 16h-3.923q0 1.285-.896 2.18T12 19.078t-2.18-.896M5 15h14q0-2.9-2.05-4.95T12 8t-4.95 2.05T5 15m8.47 2.467q.607-.61.607-1.467H9.923q0 .864.612 1.47t1.47.607t1.465-.61M12 16");
}

</style>
