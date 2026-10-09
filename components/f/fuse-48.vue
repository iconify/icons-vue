<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulm7ljbga.css';
import '../../css/p/pfm3u1bvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ulm7ljbga"/><path class="pfm3u1bvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fuse-48" /></template>
