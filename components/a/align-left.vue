<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwivelbcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gwivelbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:align-left" /></template>
