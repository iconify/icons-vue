<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgibidblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgibidblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:calendar-arrow-down" /></template>
