<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3gl5vbsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="e3gl5vbsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-edit-drawing-board-board-design-drawing-easel-process" /></template>
