<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b10x-bcrl"/><circle class="sxayvmg5s"/><circle class="d-spvrxbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:baba-is-you" /></template>
<style>
.b10x-bcrl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.514 23.953c.231-6.388 8.091-11.655 18.113-12.928c-.052-1.964-.245-3.038.003-3.731c.18-.502.607-1.025 1.61-.835c.929.176 2.504 2.147 4.352 4.472c1.005.049 3.22.06 3.22.06s.028-3.046.12-3.757c.09-.71.54-1.28 1.48-1.108c1.291.235 2.738 4.1 3.707 5.819c3.288 2.308 6.339 5.932 6.38 10.792c.034 3.886-1.203 6.004-2.451 7.798c.445 2.392 1.214 8.016 1.155 8.808c-.059.793-.688 1.475-1.386 1.58s-1.69-.154-2.146-1.193s-1.58-6.887-1.58-6.887l-3.487 1.759s1.131 4.178 1.312 5.188a1.653 1.653 0 0 1-1.252 1.908c-.698.137-1.607-.102-1.983-.954c-.376-.853-2.25-6.201-2.25-6.201l-10.822.193s-.049 3.956-.171 5.149c-.123 1.192-1.42 2.008-2.317 2.013c-.896.004-1.76-.564-1.883-1.826s-.19-5.41-.19-5.41l-2.325-.715s-2.218 6.612-2.578 7.17s-1.17.795-1.878.551c-.709-.243-1.095-1.041-.97-2.131c.126-1.09 1.457-5.421 1.67-6.127c-2.232-1.973-3.635-4.384-3.45-9.46z");
}

.d-spvrxbw {
  cx: 36.665px;
  cy: 16.402px;
  r: 1.926px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.sxayvmg5s {
  cx: 29.293px;
  cy: 20.631px;
  r: 2.176px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
