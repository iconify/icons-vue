<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj_6wwzvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rj_6wwzvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:figma-flatten-selection" /></template>
