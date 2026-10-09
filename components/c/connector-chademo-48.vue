<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg-biwbzh.css';
import '../../css/h/h1lg0z1zs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xg-biwbzh"/><path class="h1lg0z1zs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:connector-chademo-48" /></template>
