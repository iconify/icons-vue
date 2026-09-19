<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5qpf5bjd.css';
import '../../css/s/stdjlnzrk.css';
import '../../css/g/gxdbe2bxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e5qpf5bjd"/><path class="stdjlnzrk"/><path class="gxdbe2bxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:autoscaling" /></template>
