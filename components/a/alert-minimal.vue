<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kb-d9ccwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:alert-minimal" /></template>
<style>
.kb-d9ccwy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.75 4.5q0-2.75-2.75-2.75T9.25 4.5v9q0 2.75 2.75 2.75t2.75-2.75zM9.5 20q0-2.5 2.5-2.5q1.036 0 1.768.732T14.5 20t-.732 1.768T12 22.5q-2.5 0-2.5-2.5");
}

</style>
