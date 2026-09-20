<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k19iyebqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k19iyebqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:arrow-right-box-sharp" /></template>
