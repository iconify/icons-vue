<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgxld1aoi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xgxld1aoi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:add-mode" /></template>
