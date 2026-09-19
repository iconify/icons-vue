<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpfw_zbye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jpfw_zbye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:bounding-box-circles" /></template>
