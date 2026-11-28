<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmrqhabvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmrqhabvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:hotel-x" /></template>
