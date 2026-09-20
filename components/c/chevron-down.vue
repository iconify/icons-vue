<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0iiyl8ji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0iiyl8ji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:chevron-down" /></template>
