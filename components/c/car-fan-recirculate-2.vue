<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxsu58boe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:car-fan-recirculate-2" /></template>
<style>
.mxsu58boe {
  fill: currentColor;
  d: path("m9.385 14.442l.607-.626l-.944-.893h2.596q1.008 0 1.74-.703q.731-.703.731-1.691q0-1.008-.722-1.71q-.722-.703-1.749-.703H7.75v.865h3.894q.652 0 1.12.457t.467 1.09t-.467 1.081t-1.12.449H9.048l.944-.906l-.608-.613l-2 1.942zM6.75 19q-.89 0-1.606-.518q-.715-.518-1.121-1.328H1v-4.942q0-.69.463-1.153t1.152-.463h1.116l1.538-4.155q.167-.427.545-.684T6.65 5.5h7.123q.39 0 .718.195t.546.51l2.424 3.91l3.964.312q.69.056 1.133.539q.442.482.442 1.173v5.015h-3.042q-.387.81-1.102 1.328T17.25 19t-1.606-.518t-1.121-1.328H9.458q-.387.81-1.102 1.328T6.75 19");
}

</style>
