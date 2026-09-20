<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sg_cwepzi.css';
import '../../css/u/un_5q0boj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sg_cwepzi"/><path class="un_5q0boj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-archive-open" /></template>
