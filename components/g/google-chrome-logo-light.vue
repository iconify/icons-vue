<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="n6kympb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:google-chrome-logo-light" /></template>
<style>
.n6kympb4q {
  fill: currentColor;
  d: path("M128 26a102 102 0 1 0 102 102A102.12 102.12 0 0 0 128 26m0 12a90 90 0 0 1 77.33 44H128a46.07 46.07 0 0 0-44.93 36.17l-26.16-45.3A89.91 89.91 0 0 1 128 38m34 90a34 34 0 1 1-34-34a34 34 0 0 1 34 34m-124 0a89.4 89.4 0 0 1 11.5-44l38.66 67c.06.1.13.18.19.27A45.94 45.94 0 0 0 142 171.83l-26.17 45.34A90.13 90.13 0 0 1 38 128m91.16 90l38.68-67l.21-.41A45.9 45.9 0 0 0 159 94h52.37a90 90 0 0 1-82.16 124Z");
}

</style>
