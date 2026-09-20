<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc8olxbuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="sc8olxbuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-horizontal-menu-down" /></template>
