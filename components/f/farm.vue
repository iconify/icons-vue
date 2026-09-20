<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_66qz3oi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_66qz3oi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:farm" /></template>
