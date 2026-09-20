<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jd7-btbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:family-restroom-sharp" /></template>
<style>
.jd7-btbnw {
  fill: currentColor;
  d: path("M18 5.808q-.698 0-1.195-.497t-.497-1.195t.497-1.196T18 2.423t1.195.497t.497 1.196q0 .698-.497 1.195T18 5.808M16.73 21.5V11.046h-1.574l1.479-3.969h2.75l3.115 8.308h-2.654V21.5zm-5.158-10.459q-.38-.382-.38-.928t.383-.926t.927-.38t.926.383t.38.928t-.382.925t-.928.38t-.926-.382M5.5 5.808q-.698 0-1.195-.497t-.497-1.195t.497-1.196T5.5 2.423t1.195.497t.497 1.196q0 .698-.497 1.195T5.5 5.808M3.73 21.5v-6.577H2.078v-7.5h6.846v7.5H7.269V21.5zm7.54 0V18h-1v-5.5h4.46V18h-1v3.5z");
}

</style>
