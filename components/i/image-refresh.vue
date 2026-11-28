<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3y8m17xk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3y8m17xk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:image-refresh" /></template>
