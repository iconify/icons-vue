<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5lgtfbzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:feed-outline-sharp" /></template>
<style>
.u5lgtfbzi {
  fill: currentColor;
  d: path("M4 20V4h11.577L20 8.423V20zm1-1h14V9h-4V5H5zm2.5-3h9v-1h-9zm0-7H12V8H7.5zm0 3.5h9v-1h-9zM5 5v4zv14z");
}

</style>
