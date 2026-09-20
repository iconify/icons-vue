<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btne34iwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="btne34iwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-vertical-horizontal-stipple-down-right" /></template>
