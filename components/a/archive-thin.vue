<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="jnc7wzb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:archive-thin" /></template>
<style>
.jnc7wzb1r {
  fill: currentColor;
  d: path("M224 52H32a12 12 0 0 0-12 12v24a12 12 0 0 0 12 12h4v92a12 12 0 0 0 12 12h160a12 12 0 0 0 12-12v-92h4a12 12 0 0 0 12-12V64a12 12 0 0 0-12-12m-12 140a4 4 0 0 1-4 4H48a4 4 0 0 1-4-4v-92h168Zm16-104a4 4 0 0 1-4 4H32a4 4 0 0 1-4-4V64a4 4 0 0 1 4-4h192a4 4 0 0 1 4 4Zm-128 48a4 4 0 0 1 4-4h48a4 4 0 0 1 0 8h-48a4 4 0 0 1-4-4");
}

</style>
