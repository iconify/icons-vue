<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztoxc1bad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ztoxc1bad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:agent-compact" /></template>
