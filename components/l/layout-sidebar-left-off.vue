<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nk1oa_q5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nk1oa_q5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:layout-sidebar-left-off" /></template>
