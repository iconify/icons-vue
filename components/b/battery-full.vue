<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/op5xopbiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="op5xopbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:battery-full" /></template>
