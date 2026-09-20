<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdfnfe_oh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:last-page-outline-rounded" /></template>
<style>
.bdfnfe_oh {
  fill: currentColor;
  d: path("M10.2 12L6.3 8.1q-.275-.275-.275-.7t.275-.7t.7-.275t.7.275l4.6 4.6q.15.15.213.325t.062.375t-.062.375t-.213.325l-4.6 4.6q-.275.275-.7.275t-.7-.275t-.275-.7t.275-.7zm7.513-5.712Q18 6.575 18 7v10q0 .425-.288.713T17 18t-.712-.288T16 17V7q0-.425.288-.712T17 6t.713.288");
}

</style>
