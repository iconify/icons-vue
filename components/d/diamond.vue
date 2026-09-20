<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdyeyv2or.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fdyeyv2or"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:diamond" /></template>
