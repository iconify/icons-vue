<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sccw7vblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:avatar-edit" /></template>
<style>
.sccw7vblb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.962 11.051q-.811-.997-.942-2.376q-.188-1.981 1.151-3.453T8.5 3.75t3.329 1.472t1.151 3.453q-.131 1.379-.942 2.376Q15.25 12.978 15.25 18v2q0 1.75-1.75 1.75h-10q-1.75 0-1.75-1.75v-2q0-5.022 3.212-6.949m11.288 3.244l.173-.78q.142-.641.606-1.104l1.941-1.94q1.28-1.28 2.56 0t0 2.56l-2.02 2.02q-.344.345-.801.516l-.696.261q-.741.278-1.338-.242q-.597-.518-.425-1.29");
}

</style>
