<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iky8m_bqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iky8m_bqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dot-circle-fill" /></template>
