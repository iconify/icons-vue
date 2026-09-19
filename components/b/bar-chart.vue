<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsj5r1bqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<path class="bsj5r1bqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:bar-chart" /></template>
