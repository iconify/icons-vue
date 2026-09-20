<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m61z8jb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m61z8jb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-50-bluetooth" /></template>
