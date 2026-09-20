<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pq1wgzb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pq1wgzb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:kerb-unspecified" /></template>
