<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjvd_wblo.css';
import '../../css/c/cibdfcbfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjvd_wblo"/><path class="cibdfcbfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:bookmark-remove" /></template>
