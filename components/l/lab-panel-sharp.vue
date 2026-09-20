<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehjmd61mh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:lab-panel-sharp" /></template>
<style>
.ehjmd61mh {
  fill: currentColor;
  d: path("M1 21v-9h2V7.725H2V3h9v4.725h-1V12h4V7.725h-1V3h9v4.725h-1V12h2v9zm15-9h3V8h-3zM5 12h3V8H5z");
}

</style>
