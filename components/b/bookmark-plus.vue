<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjvd_wblo.css';
import '../../css/l/lcovd_bbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjvd_wblo"/><path class="lcovd_bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:bookmark-plus" /></template>
