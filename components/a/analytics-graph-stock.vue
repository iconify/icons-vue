<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7v4k9b7n.css';
import '../../css/k/k1yi-x8pw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7v4k9b7n"/><path class="k1yi-x8pw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:analytics-graph-stock" /></template>
