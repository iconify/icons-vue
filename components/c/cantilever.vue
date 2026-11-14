<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g40wlhb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cantilever" /></template>
<style>
.g40wlhb0o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 1.75h-1q-2.5 0-2.5 2.5v15.5q0 1.036.732 1.768t1.768.732h1q1.036 0 1.768-.732t.732-1.768v-4.648l12.913-2.87q.062-.014.121-.038t.112-.057t.102-.076q.047-.042.087-.092t.071-.105t.052-.115t.031-.123t.011-.126V8q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T21 7.25H8.25v-3q0-1.036-.732-1.768T5.75 1.75m2.5 11.815V8.75h12v2.148z");
}

</style>
