<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_dcyk29s.css';
import '../../css/i/i3zq9bb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w_dcyk29s"/><path class="i3zq9bb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-cursor-open-light" /></template>
