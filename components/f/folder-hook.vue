<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6_kf7bqk.css';
import '../../css/v/vwhy-4s3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l6_kf7bqk"/><path class="vwhy-4s3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-hook" /></template>
