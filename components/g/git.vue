<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvj5u7dat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="bvj5u7dat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:git" /></template>
