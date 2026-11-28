<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktwa__6uz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktwa__6uz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:book-open-minus" /></template>
