<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw5sfwb0q.css';
import '../../css/s/s_-b-lbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zw5sfwb0q"/><path class="s_-b-lbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-warning-48" /></template>
