<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb-c83bqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sb-c83bqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:chopping-board" /></template>
