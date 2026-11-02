<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz-vx1bre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oz-vx1bre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-center-vertical-fill" /></template>
