<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-xocr45f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="j-xocr45f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:behance" /></template>
