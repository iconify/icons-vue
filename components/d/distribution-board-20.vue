<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsw1rgb1l.css';
import '../../css/x/x3xddwbyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zsw1rgb1l"/><path class="x3xddwbyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:distribution-board-20" /></template>
