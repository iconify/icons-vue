<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_ouxubdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="b_ouxubdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-horizontal-stipple-down" /></template>
