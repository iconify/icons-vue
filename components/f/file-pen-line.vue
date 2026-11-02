<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_h2uabbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_h2uabbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-pen-line" /></template>
