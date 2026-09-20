<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjpr25u-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zjpr25u-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:file-search-remix" /></template>
