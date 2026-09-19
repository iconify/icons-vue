<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/du3ndgb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="du3ndgb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:goblet" /></template>
