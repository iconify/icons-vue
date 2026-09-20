<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgcwbvbsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rgcwbvbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bridge-shape-diagonal" /></template>
