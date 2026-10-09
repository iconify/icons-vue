<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/weah0ec9g.css';
import '../../css/d/d29jj3bil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="weah0ec9g"/><path class="d29jj3bil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-warning-48-bold" /></template>
