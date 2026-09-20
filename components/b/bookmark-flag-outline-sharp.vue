<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t182mm-vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bookmark-flag-outline-sharp" /></template>
<style>
.t182mm-vc {
  fill: currentColor;
  d: path("M9.5 14H11v-3h4.5L14 9l1.5-2h-6zM5 21V3h14v18l-7-3zm2-3.05l5-2.15l5 2.15V5H7zM7 5h10z");
}

</style>
