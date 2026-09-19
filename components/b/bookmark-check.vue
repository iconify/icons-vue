<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjvd_wblo.css';
import '../../css/a/a1124ulky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjvd_wblo"/><path class="a1124ulky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:bookmark-check" /></template>
