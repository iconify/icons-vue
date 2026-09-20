<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nf0zsz4hs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cart-16-filled" /></template>
<style>
.nf0zsz4hs {
  fill: currentColor;
  d: path("M2.5 2a.5.5 0 0 0 0 1h.246a.5.5 0 0 1 .48.363l1.586 5.55A1.5 1.5 0 0 0 6.254 10h4.569a1.5 1.5 0 0 0 1.393-.943l1.474-3.686A1 1 0 0 0 12.762 4H4.448l-.261-.912A1.5 1.5 0 0 0 2.746 2zm4 12a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3m4 0a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3");
}

</style>
