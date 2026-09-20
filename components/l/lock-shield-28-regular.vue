<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="xc-3nfp-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-shield-28-regular" /></template>
<style>
.xc-3nfp-m {
  fill: currentColor;
  d: path("M20.901 14.23a.895.895 0 0 1 1.198 0c.797.769 2.33 1.993 4.215 2.244c.376.05.686.336.686.695v3.355c0 4.51-4.374 6.146-5.32 6.448a.6.6 0 0 1-.359 0c-.946-.302-5.32-1.938-5.321-6.448V17.17c0-.359.31-.645.686-.695c1.884-.251 3.418-1.475 4.215-2.245M14 2a5.5 5.5 0 0 1 5.5 5.5v2.509a3.75 3.75 0 0 1 3.498 3.69l-.206-.19l-.137-.118a1.88 1.88 0 0 0-1.285-.386a2.25 2.25 0 0 0-2.12-1.505H8.75a2.25 2.25 0 0 0-2.25 2.25v8.5a2.25 2.25 0 0 0 2.25 2.25h7.457a7.8 7.8 0 0 0 1.35 1.5H8.75A3.75 3.75 0 0 1 5 22.25v-8.5a3.75 3.75 0 0 1 3.5-3.741V7.5A5.5 5.5 0 0 1 14 2m0 14.5c.396 0 .755.154 1.023.404a2 2 0 0 0-.023.266v1.945a1.5 1.5 0 1 1-1-2.615m0-13a4 4 0 0 0-4 4V10h8V7.5a4 4 0 0 0-4-4");
}

</style>
