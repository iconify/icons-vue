<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-c7f4bry.css';
import '../../css/u/un_5q0boj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s-c7f4bry"/><path class="un_5q0boj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-archive" /></template>
