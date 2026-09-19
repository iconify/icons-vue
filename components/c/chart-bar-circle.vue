<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j972wnbjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="j972wnbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:chart-bar-circle" /></template>
