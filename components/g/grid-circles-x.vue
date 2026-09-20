<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yidkjd_bo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yidkjd_bo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-circles-x" /></template>
