<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtf_51zyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtf_51zyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:low-vision" /></template>
