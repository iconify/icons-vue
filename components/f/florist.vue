<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3xearisc.css';
import '../../css/g/ga3pmjrdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3xearisc"/><path class="ga3pmjrdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:florist" /></template>
