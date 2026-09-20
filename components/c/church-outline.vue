<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4-814cbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:church-outline" /></template>
<style>
.y4-814cbg {
  fill: currentColor;
  d: path("M2 22v-8l4-1.775V9l5-2.5V5H9V3h2V1h2v2h2v2h-2v1.5L18 9v3.225L22 14v8h-9v-4q0-.425-.288-.712T12 17t-.712.288T11 18v4zm2-2h5v-2.05q0-1.275.875-2.162T12 14.9t2.125.888T15 17.95V20h5v-4.8l-4-1.8v-3.35L12 8l-4 2.05v3.35l-4 1.8zm9.063-6.937q.437-.438.437-1.063t-.437-1.062T12 10.5t-1.062.438T10.5 12t.438 1.063T12 13.5t1.063-.437M12 14");
}

</style>
