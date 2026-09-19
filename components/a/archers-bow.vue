<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktfg7-bph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ktfg7-bph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:archers-bow" /></template>
