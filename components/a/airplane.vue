<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u593zgbza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u593zgbza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:airplane" /></template>
