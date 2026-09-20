<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_g8aobdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="m_g8aobdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:cloud-down" /></template>
