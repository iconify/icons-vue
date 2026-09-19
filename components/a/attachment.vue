<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_widkvhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m_widkvhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:attachment" /></template>
