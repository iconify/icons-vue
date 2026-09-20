<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_9sbvicc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_9sbvicc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-document-arrow-right" /></template>
