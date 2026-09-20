<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_-0srbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrow-right-outline-rounded" /></template>
<style>
.k_-0srbwi {
  fill: currentColor;
  d: path("M10.5 16.3q-.2 0-.35-.137T10 15.8V8.2q0-.225.15-.362t.35-.138q.05 0 .35.15l3.625 3.625q.125.125.175.25t.05.275t-.05.275t-.175.25L10.85 16.15q-.075.075-.162.113t-.188.037");
}

</style>
