<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5sxvgbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":27,"height":24};
const content = `<path class="m5sxvgbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:checkbox-active" /></template>
