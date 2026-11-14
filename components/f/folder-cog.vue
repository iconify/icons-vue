<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urhdrvr_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:folder-cog" /></template>
<style>
.urhdrvr_j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 4.25Q2.25 4.25 2.25 7v10q0 2.75 2.75 2.75h14q2.75 0 2.75-2.75V9q0-2.75-2.75-2.75h-7.189L10.03 4.47q-.105-.106-.243-.163T9.5 4.25zm5.724 6.217l.032.028l.002-.046Q10.827 9.281 12 9.281t1.242 1.171l.002.043l.032-.028q.878-.781 1.708.05q.83.829.049 1.707l-.028.032l.046.002q1.168.069 1.168 1.242t-1.171 1.242l-.043.002l.028.032q.781.878-.05 1.708q-.829.83-1.707.049l-.032-.028l-.002.046q-.069 1.168-1.242 1.168t-1.242-1.171l-.002-.043l-.032.028q-.878.781-1.708-.05q-.83-.829-.049-1.707l.028-.032l-.046-.002q-1.168-.069-1.168-1.242t1.171-1.242l.043-.002l-.028-.032q-.781-.878.05-1.708q.829-.83 1.707-.049");
}

</style>
