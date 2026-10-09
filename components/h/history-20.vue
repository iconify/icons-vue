<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thr7ovb8q.css';
import '../../css/o/ogpkn9bgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="thr7ovb8q"/><path class="ogpkn9bgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:history-20" /></template>
