<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2wi0sz4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j2wi0sz4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:loading-one" /></template>
