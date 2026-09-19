<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1rte6bvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="bookmark-outline"><path class="Vector i1rte6bvi" clip-rule="evenodd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:bookmark-outline" /></template>
