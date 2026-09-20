<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8hbppn9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:girl-outline" /></template>
<style>
.z8hbppn9j {
  fill: currentColor;
  d: path("M11.032 7.099q-.397-.401-.397-.968t.4-.965t.969-.397t.964.401q.398.401.398.968t-.401.965t-.969.397t-.964-.401m-.378 11.863v-3.808H8.942l2.049-5.875q.123-.327.394-.514q.271-.188.612-.188q.342 0 .616.188t.397.514l2.048 5.875h-1.712v3.808z");
}

</style>
