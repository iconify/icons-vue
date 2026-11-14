<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spfnm5bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:folder-video" /></template>
<style>
.spfnm5bcp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 4.25Q2.25 4.25 2.25 7v10q0 2.75 2.75 2.75h14q2.75 0 2.75-2.75V9q0-2.75-2.75-2.75h-7.189L10.03 4.47q-.105-.106-.243-.163T9.5 4.25zm7.895 6.191l1.052.622q1.104.654 1.104 1.937t-1.104 1.937l-1.052.622q-1.126.664-2.261.017Q9.5 14.928 9.5 13.621v-1.242q0-1.307 1.134-1.955q1.135-.647 2.261.017");
}

</style>
