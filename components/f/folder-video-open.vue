<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv8-lrn5y.css';
import '../../css/r/rh3qbgbhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xv8-lrn5y"/><path class="rh3qbgbhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-video-open" /></template>
