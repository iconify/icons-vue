<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jom4w58hj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jom4w58hj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:color-filter-line" /></template>
