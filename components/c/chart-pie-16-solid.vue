<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8wbxwy2x.css';
import '../../css/c/clxvp5dwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y8wbxwy2x"/><path class="clxvp5dwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chart-pie-16-solid" /></template>
