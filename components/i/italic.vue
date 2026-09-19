<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6m_etbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="y6m_etbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:italic" /></template>
