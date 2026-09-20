<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjmap7bco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjmap7bco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:battery-low-sharp" /></template>
