<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myddi0u4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="myddi0u4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:level-five-title" /></template>
