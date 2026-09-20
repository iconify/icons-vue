<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu4zy5bik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xu4zy5bik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:camera-switch-line" /></template>
