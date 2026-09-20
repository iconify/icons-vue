<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbf0xbc8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wbf0xbc8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:filter-1" /></template>
