<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohs7hsjpb.css';
import '../../css/s/sdzy7xbyh.css';
import '../../css/j/j3w9z2dlq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ohs7hsjpb"/><path class="sdzy7xbyh"/><path class="j3w9z2dlq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fire-engine-48" /></template>
