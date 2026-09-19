<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pol0z9bwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pol0z9bwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:copilot-warning" /></template>
