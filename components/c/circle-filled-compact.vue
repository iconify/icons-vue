<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfbl99j8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="dfbl99j8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:circle-filled-compact" /></template>
