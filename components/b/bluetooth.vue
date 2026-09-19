<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0m_jxb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0m_jxb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:bluetooth" /></template>
