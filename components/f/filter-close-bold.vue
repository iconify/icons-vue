<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry1vzxbgx.css';
import '../../css/h/hllb8zubv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ry1vzxbgx"/><path class="hllb8zubv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:filter-close-bold" /></template>
