<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihyqh-94e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihyqh-94e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:camera-star" /></template>
