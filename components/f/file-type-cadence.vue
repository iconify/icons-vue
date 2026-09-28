<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="nj1r9sboj"><path class="vx24yfbrw"/><path class="r2tu9wioj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-cadence" /></template>
<style>
.nj1r9sboj {
  fill: var(--svg-color--00db80, #00db80);
}

.r2tu9wioj {
  d: path("M18.56 24.507a1.083 1.078 0 0 1-.744.31H7.61a.5.499 0 0 1-.515-.54v-9.904q.014-.404.339-.727l3.465-3.396H4.645L2.371 12.5a1.083 1.078 0 0 0-.365.782v15.725q0 .405.243.634a.948.943 0 0 0 .623.242h15.932c.27 0 .568-.121.785-.337l2.166-2.196v-5.74ZM29.159 2.003H13.213q-.406.014-.771.35L8.435 6.45h16.379c.446 0 .758.324.758.795l-.054 16.332l4.142-4.016a1.218 1.213 0 0 0 .338-.781V2.88a.812.809 0 0 0-.84-.877");
}

.vx24yfbrw {
  d: path("M17.924 10.883h3.046q.121 0 .135.095v2.749q.013.256-.135.444l-6.01 6.024q-.19.161-.42.188h-2.856q-.136 0-.136-.121l.014-3.018q0-.216.176-.378l5.793-5.767q.176-.202.406-.216z");
}

</style>
