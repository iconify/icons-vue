<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uh92myd5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:4k-sharp" /></template>
<style>
.uh92myd5v {
  fill: currentColor;
  d: path("M12.885 14.692h.884v-2.365l2.289 2.365h1.211l-2.634-2.73l2.634-2.654h-1.173l-2.327 2.327V9.308h-.885zm-3.231 0h.885v-1.5h1.23v-.884h-1.23v-3h-.885v3H7.769v-3h-.884v3.884h2.769zM4 20V4h16v16z");
}

</style>
