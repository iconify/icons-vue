<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyy95cbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyy95cbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:car-convertible" /></template>
