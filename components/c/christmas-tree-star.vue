<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u17wqacrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u17wqacrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:christmas-tree-star" /></template>
