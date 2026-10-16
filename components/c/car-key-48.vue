<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bazb3ccgr.css';
import '../../css/y/yy05a9bqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bazb3ccgr"/><path class="yy05a9bqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:car-key-48" /></template>
