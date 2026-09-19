<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncg4ydbbh.css';
import '../../css/r/r2vjdgbir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncg4ydbbh"/><path class="r2vjdgbir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-django" /></template>
