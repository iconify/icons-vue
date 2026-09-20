<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qefbcuy_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qefbcuy_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:bus" /></template>
