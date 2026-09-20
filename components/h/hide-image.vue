<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvaeiwqxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hide-image" /></template>
<style>
.hvaeiwqxh {
  fill: currentColor;
  d: path("M20 17.15L6.85 4h11.535q.69 0 1.153.463T20 5.616zm.492 4.758L18.585 20H5.615q-.69 0-1.152-.462T4 18.384V5.416L2.092 3.508L2.8 2.8l18.4 18.4zM7.5 16.5h7.579l-2.35-2.35l-1.517 1.889l-1.75-2.116z");
}

</style>
