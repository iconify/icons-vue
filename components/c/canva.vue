<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqi20zl9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqi20zl9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:canva" /></template>
