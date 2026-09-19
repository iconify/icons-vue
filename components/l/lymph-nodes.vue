<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq-v7yb2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qq-v7yb2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:lymph-nodes" /></template>
