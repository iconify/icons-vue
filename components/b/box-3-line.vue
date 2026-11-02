<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1r9m9brd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1r9m9brd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:box-3-line" /></template>
