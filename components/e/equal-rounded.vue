<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9aiwsnho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:equal-rounded" /></template>
<style>
.f9aiwsnho {
  fill: currentColor;
  d: path("M6 16q-.417 0-.708-.291Q5 15.418 5 15.002t.292-.709T6 14h12q.417 0 .708.291q.292.291.292.707t-.292.709T18 16zm0-6q-.417 0-.708-.291Q5 9.418 5 9.002t.292-.709T6 8h12q.417 0 .708.291q.292.291.292.707t-.292.709T18 10z");
}

</style>
