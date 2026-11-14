<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8vs54b9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:control-arm" /></template>
<style>
.u8vs54b9q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 2.75q-2.75 0-2.75 2.75q0 2.345 2 2.69v7.62q-2 .345-2 2.69q0 2.75 2.75 2.75t2.75-2.75q0-.187-.013-.361l9.98-4.339q.666.95 2.283.95q2.75 0 2.75-2.75T19.5 9.25q-1.617 0-2.283.95l-9.98-4.339q.013-.174.013-.361q0-2.75-2.75-2.75m.75 13.06V8.19q1.034-.178 1.533-.89l9.98 4.339q-.013.174-.013.361t.013.361L6.783 16.7q-.499-.712-1.533-.89");
}

</style>
