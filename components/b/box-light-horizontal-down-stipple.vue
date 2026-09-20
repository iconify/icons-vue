<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdte0c4ry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="wdte0c4ry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-horizontal-down-stipple" /></template>
