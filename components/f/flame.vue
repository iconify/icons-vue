<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9z4m6_0r.css';
import '../../css/j/j1jrbccvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":180,"height":180};
const content = `<path class="j9z4m6_0r"/><path class="j1jrbccvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:flame" /></template>
