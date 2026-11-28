<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkq-xq00b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zkq-xq00b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:file-chart-column-solid" /></template>
