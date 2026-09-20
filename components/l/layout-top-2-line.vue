<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvi7wnmts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvi7wnmts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:layout-top-2-line" /></template>
