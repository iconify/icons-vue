<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyyhb3b_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xyyhb3b_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:editor-paste-text" /></template>
