<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je1y2wbjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="je1y2wbjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:charge" /></template>
