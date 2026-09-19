<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9jb0-bzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="h9jb0-bzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:cursor" /></template>
