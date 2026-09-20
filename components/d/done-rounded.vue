<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tge7gjbul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:done-rounded" /></template>
<style>
.tge7gjbul {
  fill: currentColor;
  d: path("m9.55 15.88l8.802-8.801q.146-.146.344-.156t.363.156t.166.357t-.165.356l-8.944 8.95q-.243.243-.566.243t-.566-.243l-4.05-4.05q-.146-.146-.152-.347t.158-.366t.357-.165t.357.165z");
}

</style>
