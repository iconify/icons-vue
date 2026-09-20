<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvm8og75o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:aod-tablet" /></template>
<style>
.mvm8og75o {
  fill: currentColor;
  d: path("M8.5 11.192v-.884h7v.884zm1 3v-.884h5v.884zM3.616 19q-.667 0-1.141-.475T2 17.386V6.615q0-.666.475-1.14T3.614 5h16.77q.666 0 1.14.475T22 6.615v10.77q0 .666-.475 1.14t-1.14.475zM5.5 18h13V6h-13z");
}

</style>
