<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3xw3800t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:checked-bag-sharp" /></template>
<style>
.s3xw3800t {
  fill: currentColor;
  d: path("M8.192 16.385V7h1.423q0-.98.702-1.683q.702-.702 1.683-.702t1.683.702T14.385 7h1.423v9.385zM10.5 7h3q0-.65-.425-1.075T12 5.5t-1.075.425T10.5 7m6.192 9.385V7H19v9.385zM5 16.385V7h2.308v9.385zm-1.616 3v-1h17.232v1z");
}

</style>
