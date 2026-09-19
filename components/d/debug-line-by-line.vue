<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0l5uqr_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k0l5uqr_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:debug-line-by-line" /></template>
