<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnp6eqb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:decimal-increase-fill-round" /></template>
<style>
.xnp6eqb7r {
  fill: currentColor;
  d: path("M6 5a3 3 0 1 1 6 0v2a3 3 0 1 1-6 0Zm8 0a3 3 0 1 1 6 0v2a3 3 0 1 1-6 0ZM8 5v2a1 1 0 0 0 2 0V5a1 1 0 0 0-2 0m8 0v2a1 1 0 0 0 2 0V5a1 1 0 0 0-2 0M3 8h.01a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m14.293 12.293L18.586 19H3a1 1 0 0 1 0-2h15.586l-1.293-1.293a1 1 0 0 1 1.414-1.414l3 3a1 1 0 0 1 0 1.414l-3 3a.999.999 0 1 1-1.414-1.414");
}

</style>
