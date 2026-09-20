<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uasfyh6se"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:border-top-bottom-double-24-filled" /></template>
<style>
.uasfyh6se {
  fill: currentColor;
  d: path("M3 6a1 1 0 0 0 2 0a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1a1 1 0 1 0 2 0a3 3 0 0 0-3-3H6a3 3 0 0 0-3 3m2 5a1 1 0 1 0-2 0v2a1 1 0 1 0 2 0zm-1 7a1 1 0 1 1 0-2h16a1 1 0 1 1 0 2zm0 3a1 1 0 1 1 0-2h16a1 1 0 1 1 0 2zm16-11a1 1 0 0 0-1 1v2a1 1 0 1 0 2 0v-2a1 1 0 0 0-1-1");
}

</style>
