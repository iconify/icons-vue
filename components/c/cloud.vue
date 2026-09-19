<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu_b0rb6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1920,"height":1408};
const content = `<path class="zu_b0rb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:cloud" /></template>
