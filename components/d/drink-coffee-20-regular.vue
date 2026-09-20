<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kn45qxbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:drink-coffee-20-regular" /></template>
<style>
.kn45qxbff {
  fill: currentColor;
  d: path("M5 2.5a.5.5 0 0 0-1 0c0 1.002.686 1.515 1.16 1.87l.04.03c.526.394.8.63.8 1.1a.5.5 0 0 0 1 0c0-1.002-.686-1.515-1.16-1.87L5.8 3.6c-.526-.394-.8-.63-.8-1.1m10 5.435V9h1a3 3 0 1 1 0 6h-1.803A6 6 0 0 1 3 12V7.935C3 7.419 3.419 7 3.935 7h10.13c.517 0 .935.419.935.935M4 8v4a5 5 0 0 0 10 0V8zm11 4a6 6 0 0 1-.341 2H16a2 2 0 1 0 0-4h-1zM7.5 2a.5.5 0 0 1 .5.5c0 .47.274.706.8 1.1l.04.03c.474.355 1.16.868 1.16 1.87a.5.5 0 0 1-1 0c0-.47-.274-.706-.8-1.1l-.04-.03C7.686 4.015 7 3.502 7 2.5a.5.5 0 0 1 .5-.5m3.5.5a.5.5 0 0 0-1 0c0 1.002.686 1.515 1.16 1.87l.04.03c.526.394.8.63.8 1.1a.5.5 0 0 0 1 0c0-1.002-.686-1.515-1.16-1.87l-.04-.03c-.526-.394-.8-.63-.8-1.1");
}

</style>
