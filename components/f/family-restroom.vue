<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3k4u8b9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:family-restroom" /></template>
<style>
.t3k4u8b9r {
  fill: currentColor;
  d: path("M18 5.808q-.698 0-1.195-.497t-.497-1.195t.497-1.196T18 2.423t1.195.497t.497 1.196q0 .698-.497 1.195T18 5.808M16.73 21.5v-7.77q0-.873-.396-1.573q-.397-.7-1.178-1.11l1.048-2.749q.2-.548.699-.885T18 7.078t1.097.327t.7.894l2.703 7.087h-2.654V21.5zm-5.158-10.459q-.38-.382-.38-.928t.383-.926t.927-.38t.926.383t.38.928t-.382.925t-.928.38t-.926-.382M5.5 5.808q-.698 0-1.195-.497t-.497-1.195t.497-1.196T5.5 2.423t1.195.497t.497 1.196q0 .698-.497 1.195T5.5 5.808M3.73 21.5v-6.577H2.078V9.039q0-.667.475-1.141t1.14-.475h3.616q.666 0 1.14.475t.475 1.14v5.885H7.269V21.5zm7.54 0V18h-1v-4.27q0-.512.358-.871t.872-.359h2q.513 0 .872.359t.359.872V18h-1v3.5z");
}

</style>
