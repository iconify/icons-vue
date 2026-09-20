<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dlbbu25gx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:game-button-r1-rounded" /></template>
<style>
.dlbbu25gx {
  fill: currentColor;
  d: path("M21 4.98v10.732q0 1.356-.977 2.322t-2.35.966H6.327q-1.372 0-2.35-.966T3 15.712V4.98zm-5.873 5.012v4.712q0 .161.125.286t.285.125t.294-.125t.133-.286V9.083q0-.09-.055-.144q-.054-.054-.144-.054h-.396q.014 0-.117.03l-1.554 1.126q-.142.092-.16.246t.073.296t.247.16t.296-.074zm-6.408 2.689h1.17l1.438 2.275q.064.09.143.144q.08.054.175.054q.255 0 .385-.218t-.024-.428l-1.289-2.04q.623-.218.938-.645t.314-1.054q0-.938-.567-1.382t-1.723-.445H8.67q-.343 0-.575.233t-.232.575v4.973q0 .17.113.3t.29.13t.315-.13q.137-.13.137-.3zm0-.756L8.7 9.758h.933q.708 0 1.072.277q.364.278.364.784q0 .531-.357.819t-1.008.287z");
}

</style>
