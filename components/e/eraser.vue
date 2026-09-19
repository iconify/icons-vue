<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz2-0f1zi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rz2-0f1zi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:eraser" /></template>
