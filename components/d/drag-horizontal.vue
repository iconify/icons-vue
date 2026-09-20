<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l24zkvows.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="l24zkvows"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:drag-horizontal" /></template>
