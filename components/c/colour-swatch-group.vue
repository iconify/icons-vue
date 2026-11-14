<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ml2pb6b4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:colour-swatch-group" /></template>
<style>
.ml2pb6b4p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 5.5v13q0 2.25 2.25 2.25h16q2.25 0 2.25-2.25V8q0-2.25-2.25-2.25h-8.64L9.586 3.531q-.053-.065-.119-.118t-.142-.089t-.158-.055Q9.084 3.25 9 3.25H4q-2.25 0-2.25 2.25m6 4.25h8.5q1.036 0 1.768.732t.732 1.768v2q0 1.036-.732 1.768t-1.768.732h-8.5q-2.5 0-2.5-2.5v-2q0-2.5 2.5-2.5");
}

</style>
