<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_gz1s1cv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="c_gz1s1cv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:alignrightedge" /></template>
