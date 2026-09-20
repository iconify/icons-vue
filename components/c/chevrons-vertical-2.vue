<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkthjaced.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tkthjaced"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:chevrons-vertical-2" /></template>
