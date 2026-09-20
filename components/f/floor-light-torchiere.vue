<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3snt3blh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3snt3blh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:floor-light-torchiere" /></template>
