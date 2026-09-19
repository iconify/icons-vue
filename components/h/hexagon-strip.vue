<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0e2o3btx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w0e2o3btx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:hexagon-strip" /></template>
