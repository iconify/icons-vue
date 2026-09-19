<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyslfvbtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pyslfvbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:file-bar-graph-fill" /></template>
