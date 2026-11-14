<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k219umb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cue-chalk" /></template>
<style>
.k219umb7o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.85 6.337q.204.108.312.312l.005.01q.082.16.082.341v10q0 .102-.027.201q-.028.098-.08.186q-.053.087-.127.158q-.075.07-.165.118l-8.5 4.5q-.165.087-.351.087t-.351-.087l-8.5-4.5q-.09-.048-.165-.118q-.074-.071-.127-.158q-.052-.088-.08-.186q-.027-.099-.027-.201V7q0-.186.087-.351l.02-.036q.108-.178.292-.276l8.5-4.5q.081-.043.17-.065T12 1.75t.181.022t.17.065zM7.75 7q0 2.5 4.25 2.5q1.627 0 2.81-.592q1.44-.72 1.44-1.908t-1.44-1.908Q13.627 4.5 12 4.5Q7.75 4.5 7.75 7");
}

</style>
