<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkzenacir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dots-three" /></template>
<style>
.lkzenacir {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 12q0-2.75 2.75-2.75T7.75 12T5 14.75T2.25 12M12 9.25q-2.75 0-2.75 2.75T12 14.75T14.75 12T12 9.25M16.25 12q0-2.75 2.75-2.75T21.75 12T19 14.75T16.25 12");
}

</style>
