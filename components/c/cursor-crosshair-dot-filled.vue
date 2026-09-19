<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzcyxtyei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzcyxtyei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cursor-crosshair-dot-filled" /></template>
