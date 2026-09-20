<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vf6r4uboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:dashboard-2-gear-outline-sharp" /></template>
<style>
.vf6r4uboe {
  fill: currentColor;
  d: path("M11 11V4h11v7zm-9 9v-7h10v7zm0-9V4h7v7zm11-2h7V6h-7zm-9 9h6v-3H4zm0-9h3V6H4zm13 13l-.3-1.5q-.3-.125-.562-.262T15.6 19.9l-1.45.45l-1-1.7l1.15-1q-.05-.325-.05-.65t.05-.65l-1.15-1l1-1.7l1.45.45q.275-.2.538-.337t.562-.263L17 12h2l.3 1.5q.3.125.563.263t.537.337l1.45-.45l1 1.7l-1.15 1q.05.325.05.65t-.05.65l1.15 1l-1 1.7l-1.45-.45q-.275.2-.537.338t-.563.262L19 22zm2.413-3.588Q20 17.826 20 17t-.587-1.412T18 15t-1.412.588T16 17t.588 1.413T18 19t1.413-.587");
}

</style>
