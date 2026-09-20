<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9wmnkk8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:kitchen-outline-sharp" /></template>
<style>
.o9wmnkk8c {
  fill: currentColor;
  d: path("M8.192 8V5.385h1V8zm0 8.116v-4.347h1v4.347zM5 21V3h14v18zm1-1h12v-9.615H6zM6 9.385h12V4H6z");
}

</style>
