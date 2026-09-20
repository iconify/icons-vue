<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw4ap45ck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:award-star-sharp" /></template>
<style>
.qw4ap45ck {
  fill: currentColor;
  d: path("M9.517 15.558L12 14.052l2.483 1.506l-.66-2.825l2.196-1.885l-2.886-.256L12 7.942l-1.133 2.65l-2.886.256l2.196 1.885zM12 21.916L9.073 19H5v-4.073L2.085 12L5 9.073V5h4.073L12 2.085L14.927 5H19v4.073L21.916 12L19 14.927V19h-4.073z");
}

</style>
