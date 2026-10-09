<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk1jq-b8e.css';
import '../../css/x/x4l5l87lu.css';
import '../../css/c/crda83b7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yk1jq-b8e"/><path class="x4l5l87lu"/><path class="crda83b7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:goal-48-bold" /></template>
