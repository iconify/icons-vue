<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccc8p6bbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccc8p6bbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:drill-check" /></template>
