<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tut_ptpft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tut_ptpft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:copilot-error" /></template>
