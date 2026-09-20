<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3lpoh0yp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3lpoh0yp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:align-center-vertical" /></template>
