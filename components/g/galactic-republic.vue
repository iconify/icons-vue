<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdq-wdb5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="fdq-wdb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:galactic-republic" /></template>
