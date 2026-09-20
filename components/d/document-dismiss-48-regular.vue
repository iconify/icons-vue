<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iwg54ibca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-dismiss-48-regular" /></template>
<style>
.iwg54ibca {
  fill: currentColor;
  d: path("M13 24c6.075 0 11 4.925 11 11s-4.925 11-11 11S2 41.075 2 35s4.925-11 11-11M24.758 4a4.25 4.25 0 0 1 3.005 1.245l10.992 10.992A4.25 4.25 0 0 1 40 19.242V39.75A4.25 4.25 0 0 1 35.75 44H22.376a13 13 0 0 0 1.884-2.5h11.49a1.75 1.75 0 0 0 1.75-1.75V20h-9.25A4.25 4.25 0 0 1 24 15.75V6.5H12.25a1.75 1.75 0 0 0-1.75 1.75v13.99a13 13 0 0 0-2.5.756V8.25A4.25 4.25 0 0 1 12.25 4zm-6.051 25.293a1 1 0 0 0-1.414 0L13 33.586l-4.293-4.293a1 1 0 1 0-1.414 1.414L11.586 35l-4.293 4.293a1 1 0 1 0 1.414 1.414L13 36.414l4.293 4.293a1 1 0 1 0 1.414-1.414L14.414 35l4.293-4.293a1 1 0 0 0 0-1.414M26.5 15.75c0 .966.784 1.75 1.75 1.75h8.232L26.5 7.518z");
}

</style>
