<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir8nhuf2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ir8nhuf2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-ring" /></template>
