<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="dwd9n6b-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:letter-circle-v-bold" /></template>
<style>
.dwd9n6b-e {
  fill: currentColor;
  d: path("M128 20a108 108 0 1 0 108 108A108.12 108.12 0 0 0 128 20m0 192a84 84 0 1 1 84-84a84.09 84.09 0 0 1-84 84m43.14-111.54l-32 80a12 12 0 0 1-22.28 0l-32-80a12 12 0 1 1 22.28-8.92L128 143.69l20.86-52.15a12 12 0 0 1 22.28 8.92");
}

</style>
