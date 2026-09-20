<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owt4qub9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:edit-arrow-up-sharp" /></template>
<style>
.owt4qub9w {
  fill: currentColor;
  d: path("M18.5 20V7.8l-1.1 1.1L16 7.5L19.5 4L23 7.5l-1.425 1.4L20.5 7.825V20zM3 18v-4.075l7.375-7.35q.6-.6 1.438-.575t1.412.625l1.2 1.25q.575.575.563 1.4t-.588 1.4L7.075 18zm8.725-7.475l1.25-1.275l-1.225-1.225l-1.275 1.25z");
}

</style>
