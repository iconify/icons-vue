<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4l-b7bmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4l-b7bmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:language-php" /></template>
