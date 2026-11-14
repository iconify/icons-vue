<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjrunbo8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:flea-treatment" /></template>
<style>
.qjrunbo8n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.75 4.5V3.25q0-1.75 1.75-1.75h3q1.75 0 1.75 1.75V4.5H16q2.25 0 2.25 2.25v3.5q0 .161-.066.307q-.066.147-.186.254l-4.5 4q-.103.091-.231.14Q13.138 15 13 15h-2q-.138 0-.267-.049q-.128-.049-.231-.14l-4.5-4q-.12-.107-.186-.254q-.066-.146-.066-.307v-3.5Q5.75 4.5 8 4.5zm5 0h-3.5V3.25q0-.25.25-.25h3q.25 0 .25.25zM12.6 16.05l1.483 1.977q1.713 1.966-.179 3.781q-1.904 1.825-3.808 0q-1.892-1.815-.179-3.781L11.4 16.05q.044-.059.099-.108q.055-.05.119-.087q.063-.038.133-.063q.07-.024.143-.034t.147-.007t.145.022t.138.051t.126.076q.086.064.15.15");
}

</style>
