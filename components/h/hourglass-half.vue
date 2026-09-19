<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8yi72bsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="q8yi72bsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hourglass-half" /></template>
