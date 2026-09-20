<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6n4-vioi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:local-pizza" /></template>
<style>
.s6n4-vioi {
  fill: currentColor;
  d: path("M12 20.192L3.346 7.231q1.875-1.473 4.066-2.352Q9.605 4 12 4t4.588.866q2.19.867 4.066 2.365zM9.553 9.132q.293-.291.293-.707t-.29-.709t-.707-.293t-.71.291t-.293.707t.291.709t.707.293t.709-.291m3.154 5.077q.293-.291.293-.707t-.291-.709t-.707-.293t-.709.291t-.293.707t.291.709t.707.293t.709-.291");
}

</style>
