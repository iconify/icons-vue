<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y00tgva6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:baby-spoon" /></template>
<style>
.y00tgva6a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.557 11.007q-2.088 2.789-4.899 2.553l-3.502 6.304q-.015.027-.032.052q-.583.875-1.312 1.02t-1.603-.437q-1.749-1.166-.583-2.915q.027-.04.058-.076l4.685-5.388q-1.089-2.711.738-5.756q.02-.033.043-.064q1.25-1.667 2.994-2.148q1.792-.494 3.049.492q1.433.972 1.555 2.806q.121 1.808-1.148 3.5zM6.851 18.451q-.293.478.19.8q.49.326.82-.145l2.793-5.028z");
}

</style>
