<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6dd8jb9u.css';
import '../../css/o/oaiisxbfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l6dd8jb9u"/><path class="oaiisxbfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:captions-20-bold" /></template>
