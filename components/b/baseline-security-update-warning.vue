<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e41ip5b0d"/><path class="akfxyttyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-security-update-warning" /></template>
<style>
.akfxyttyf {
  fill: currentColor;
  d: path("M17 1H7c-1.1 0-1.99.9-1.99 2v18c0 1.1.89 2 1.99 2h10c1.1 0 2-.9 2-2V3c0-1.1-.9-2-2-2m0 17H7V6h10z");
}

.e41ip5b0d {
  fill: currentColor;
  d: path("M11 15h2v2h-2zm0-8h2v6h-2z");
}

</style>
