<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jic3_cbyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jic3_cbyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:duckdb" /></template>
