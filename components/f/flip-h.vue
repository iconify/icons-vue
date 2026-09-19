<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izlo61v6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="izlo61v6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:flip-h" /></template>
