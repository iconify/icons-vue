<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtue6_b5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="qtue6_b5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:camera-rotate" /></template>
