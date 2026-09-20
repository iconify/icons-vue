<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ij9c60bqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:game-button-r1" /></template>
<style>
.ij9c60bqn {
  fill: currentColor;
  d: path("M21 4.98v10.732q0 1.356-.977 2.322t-2.35.966H6.327q-1.372 0-2.35-.966T3 15.712V4.98zm-5.873 10.136h.837V8.885h-.656L13.39 10.28l.455.629l1.281-.918zm-7.263.038h.855V12.68h1.17l1.555 2.473h.99l-1.717-2.687q.624-.217.938-.645q.314-.427.314-1.053q0-.938-.567-1.383t-1.723-.444H7.864zm.855-3.229L8.7 9.758h.933q.708 0 1.072.277q.364.278.364.784q0 .531-.357.819t-1.008.287z");
}

</style>
