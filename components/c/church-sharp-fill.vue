<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v12n4ibwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:church-sharp-fill" /></template>
<style>
.v12n4ibwb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 1V3H15V5H13V7.11L18.59 11.19C18.847 11.38 19 11.68 19 12V13.38L22.447 15.11C22.786 15.27 23 15.62 23 16V22C23 22.55 22.552 23 22 23H2C1.448 23 1 22.55 1 22V16C1 15.62 1.214 15.27 1.553 15.11L5 13.38V12C5 11.68 5.153 11.38 5.41 11.19L11 7.11V5H9V3H11V1H13ZM12 16C10.895 16 10 16.9 10 18V21H14V18C14 16.9 13.105 16 12 16Z");
}

</style>
