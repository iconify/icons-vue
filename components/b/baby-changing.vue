<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_22nzb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:baby-changing" /></template>
<style>
.f_22nzb-p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 5.25q0-2-2-2t-2 2v15q0 2 2 2q1.558 0 1.902-1.214l10.002-4.286h4.596q2 0 2-2q0-1.732-1.5-1.964V11.5q0-2.75-2.75-2.75h-3.25q-1.923 0-2.501 1.344L12.25 10q.001-1.346-.951-2.299q-.373-.373-.806-.599q.024-.173-.031-.339q-.419-1.257-1.753-.893q-1.004.274-1.174 1.217q-.449.23-.834.614q-.95.951-.951 2.295zm6.255 6.015Q12 11.38 12 11.5v1.25h-1.254q.291-.19.553-.451q.468-.469.706-1.034M13.5 12.75V11.5q0-1.25 1.25-1.25H18q1.25 0 1.25 1.25v1.25zm-7.75-2.747q0 1.344.951 2.296q.262.261.553.451H6.25q-.268 0-.5.036zm6.096 6.747L5.75 19.363v-2.649q.232.036.5.036z");
}

</style>
