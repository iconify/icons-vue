<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn_6ly9xj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tn_6ly9xj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:circuit-board" /></template>
