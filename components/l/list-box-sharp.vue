<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qn5ole7cq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qn5ole7cq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:list-box-sharp" /></template>
