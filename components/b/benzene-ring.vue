<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyhxs739x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:benzene-ring" /></template>
<style>
.pyhxs739x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m19.747 6.095l-6.5-3.742q-1.247-.718-2.494 0l-6.5 3.742Q3 6.816 3 8.262v7.476q0 1.446 1.253 2.167l6.5 3.742q1.247.718 2.494 0l6.5-3.742Q21 17.184 21 15.738V8.262q0-1.446-1.253-2.167M6.5 12q0-2.278 1.611-3.889T12 6.5t3.889 1.611T17.5 12t-1.611 3.889T12 17.5t-3.889-1.611T6.5 12");
}

</style>
