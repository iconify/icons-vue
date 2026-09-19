<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oiso72bor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:logfox" /></template>
<style>
.oiso72bor {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 13.933c3.356 0 6.181.618 6.181.618s2.694-4.636 9.184-9.051c0 0-1.369 12.848 3.047 24.637c0 0-11.524 4.15-18.412 12.363c-6.888-8.212-18.412-12.363-18.412-12.363C10.004 18.348 8.635 5.5 8.635 5.5c6.49 4.415 9.184 9.051 9.184 9.051s2.825-.618 6.181-.618");
}

</style>
