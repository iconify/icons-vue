<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jinneybch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jinneybch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:camera-off" /></template>
