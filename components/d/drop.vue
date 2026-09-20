<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyent6gbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="fyent6gbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:drop" /></template>
