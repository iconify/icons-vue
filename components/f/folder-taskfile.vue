<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib3jzhgvb.css';
import '../../css/d/debdggzbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ib3jzhgvb"/><path class="debdggzbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-taskfile" /></template>
