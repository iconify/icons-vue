<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aq57wfcfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fog-cannon" /></template>
<style>
.aq57wfcfn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.203 13.028Q4.962 14.25 3.5 14.25q-1.75 0-1.75-1.75V5q0-1.75 1.75-1.75q1.416 0 1.686 1.146q.459-.146 1.064-.146h3.5q2.184 0 2.46 1.908l.261-.104q.819-.328 1.549.166t.73 1.376v2.308q0 .882-.73 1.376t-1.549.166l-.284-.114q-.152.669-.669 1.186q-.732.732-1.768.732h-3.5q-.57 0-1.047-.222M14.75 8.75q0-2.25 2.25-2.25t2.25 2.25T17 11t-2.25-2.25m1.147 3.788q-2.217.302-2.961 2.263q-2.707.39-2.558 3.361q.162 3.238 3.39 3.088h4.966q3.607.147 3.764-3.467q.149-3.418-3.067-3.753q-1.249-1.804-3.534-1.492");
}

</style>
