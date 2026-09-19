<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxlk60b9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1792};
const content = `<path class="gxlk60b9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:clip-note" /></template>
