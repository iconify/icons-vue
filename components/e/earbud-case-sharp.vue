<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ya8fkybqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:earbud-case-sharp" /></template>
<style>
.ya8fkybqc {
  fill: currentColor;
  d: path("M3 12v5q0 1.65 1.175 2.825T7 21h10q1.65 0 2.825-1.175T21 17v-5h-4v4H7v-4zm6 0v2h6v-2zm-6-2h18V7q0-1.65-1.175-2.825T17 3H7Q5.35 3 4.175 4.175T3 7z");
}

</style>
