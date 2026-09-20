<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycdk8iqtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":984.7,"height":175.5};
const content = `<path class="ycdk8iqtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:hymer" /></template>
