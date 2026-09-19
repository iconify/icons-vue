<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0d_fibqc.css';
import '../../css/j/jgmlxzbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0d_fibqc"/><path class="jgmlxzbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-in-right-circle-half" /></template>
