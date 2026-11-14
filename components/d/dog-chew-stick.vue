<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvgxpcczn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dog-chew-stick" /></template>
<style>
.uvgxpcczn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.553 6.697q0-3.75 3.75-3.75q1.553 0 2.652 1.098q1.098 1.099 1.098 2.652t-1.098 2.652t-2.652 1.098q-.468 0-.877-.058q-.173.54-.714 1.08l-4.243 4.243q-.557.558-1.115.724q.093.414.093.867q.001 1.553-1.098 2.652t-2.652 1.099t-2.652-1.099q-1.098-1.098-1.098-2.652t1.098-2.652t2.652-1.099q.453 0 .867.093q.167-.557.724-1.114l4.243-4.243q.54-.541 1.08-.714q-.058-.409-.058-.877");
}

</style>
