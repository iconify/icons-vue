<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="byevw6vdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ink-eraser-off-sharp" /></template>
<style>
.byevw6vdr {
  fill: currentColor;
  d: path("M19.775 22.625L15.05 17.9L13 20H4.75L1.2 16.45l6.1-6.3l-5.925-5.925L2.8 2.8l18.4 18.4zm-1.9-7.6L10.1 7.25l4.9-5.1l7.8 7.8z");
}

</style>
