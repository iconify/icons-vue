<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2m_4_bbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t2m_4_bbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-fog-round" /></template>
