<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sf335qbes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:camera-rear-outline-sharp" /></template>
<style>
.sf335qbes {
  fill: currentColor;
  d: path("m10.35 21.808l-.708-.708l1.6-1.6H6v-1h5.242l-1.6-1.6l.708-.708L13.158 19zM14 19.5v-1h4v1zM6 17V3h12v4.83h.923v3.686H18V17h-1V4H7v13zm6.588-9.914q.22-.222.22-.549t-.222-.547t-.549-.22t-.548.22t-.22.55t.222.547t.549.22t.548-.22");
}

</style>
