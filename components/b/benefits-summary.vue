<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7njml_mo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:benefits-summary" /></template>
<style>
.g7njml_mo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 13v6.5a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V13Zm0 0l-1.25-2.25M20 13l1.25-2.25M12 13v8.5m-7.75-14a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m8.117-3.381l.016.036a1.5 1.5 0 0 0 1.253.911l.039.003a.399.399 0 0 1 .227.699l-.03.026a1.5 1.5 0 0 0-.478 1.473l.009.039a.399.399 0 0 1-.595.431l-.033-.02a1.5 1.5 0 0 0-1.55 0l-.033.02a.399.399 0 0 1-.595-.431l.009-.039a1.5 1.5 0 0 0-.478-1.473l-.03-.026a.399.399 0 0 1 .227-.699l.039-.003a1.5 1.5 0 0 0 1.253-.911l.016-.036a.399.399 0 0 1 .734 0M18.75 9.5l-2-2a1.25 1.25 0 0 1 2-1.5a1.25 1.25 0 0 1 2 1.5Z");
}

</style>
