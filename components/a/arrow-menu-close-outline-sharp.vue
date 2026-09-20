<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fu6jrdbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrow-menu-close-outline-sharp" /></template>
<style>
.fu6jrdbix {
  fill: currentColor;
  d: path("M11 17V7l-5 5zm2 4h2V3h-2z");
}

</style>
