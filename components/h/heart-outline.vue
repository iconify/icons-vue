<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8ab7fbau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t8ab7fbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:heart-outline" /></template>
