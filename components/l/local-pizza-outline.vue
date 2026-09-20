<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r89t4jb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:local-pizza-outline" /></template>
<style>
.r89t4jb4v {
  fill: currentColor;
  d: path("M12 20.192L3.346 7.231q1.875-1.473 4.066-2.352Q9.605 4 12 4t4.588.866q2.19.867 4.066 2.365zm0-1.792l7.3-10.95q-1.625-1.125-3.475-1.787T12 5t-3.812.663T4.7 7.45zM9.553 9.132q.293-.291.293-.707t-.29-.709t-.707-.293t-.71.291t-.293.707t.291.709t.707.293t.709-.291m3.154 5.077q.293-.291.293-.707t-.291-.709t-.707-.293t-.709.291t-.293.707t.291.709t.707.293t.709-.291M12 18.4");
}

</style>
