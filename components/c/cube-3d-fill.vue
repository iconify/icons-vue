<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c06-m_bfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c06-m_bfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cube-3d-fill" /></template>
