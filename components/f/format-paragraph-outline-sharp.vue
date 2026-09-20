<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwtqe4i6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-paragraph-outline-sharp" /></template>
<style>
.zwtqe4i6g {
  fill: currentColor;
  d: path("M10.346 18.923V13h-.192q-1.671 0-2.836-1.164Q6.154 10.67 6.154 9t1.164-2.835T10.154 5h6.423v1h-2v12.923h-1V6h-2.23v12.923z");
}

</style>
