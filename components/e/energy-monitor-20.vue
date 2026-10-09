<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5nifvbes.css';
import '../../css/w/wewzkacif.css';
import '../../css/p/ptha_9bng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z5nifvbes"/><path class="wewzkacif"/><path class="ptha_9bng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:energy-monitor-20" /></template>
