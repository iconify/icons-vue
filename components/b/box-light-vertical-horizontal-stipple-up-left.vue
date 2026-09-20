<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x76j6m_vu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="x76j6m_vu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-vertical-horizontal-stipple-up-left" /></template>
