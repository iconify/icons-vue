<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikn_s50ly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heading-6-fill-sharp" /></template>
<style>
.ikn_s50ly {
  fill: currentColor;
  d: path("M4 5v6h6V5a1 1 0 0 1 2 0v14a1 1 0 0 1-2 0v-6H4v6a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0m10 11v-4a4 4 0 0 1 4-4h2a1 1 0 0 1 0 2h-2a2 2 0 0 0-2 2v.535A4.002 4.002 0 0 1 21.464 18A4 4 0 0 1 14 16m2.157.778a2 2 0 1 0 3.686-1.556a2 2 0 0 0-3.686 1.556");
}

</style>
