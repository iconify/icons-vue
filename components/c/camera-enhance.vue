<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk6n46bvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kk6n46bvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:camera-enhance" /></template>
