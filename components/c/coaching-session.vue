<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zljhnqxiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:coaching-session" /></template>
<style>
.zljhnqxiv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20 5.75H9q-3.286 0-5.453 2.472q-2.166 2.471-1.734 5.729t3.165 5.081q2.735 1.823 5.908.968t4.622-3.805q1.2-2.444.538-4.945H20q1.75 0 1.75-1.75v-2q0-1.75-1.75-1.75M6.25 13q0-2.75 2.75-2.75T11.75 13T9 15.75T6.25 13");
}

</style>
