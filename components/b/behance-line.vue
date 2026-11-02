<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7m_yzbll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7m_yzbll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:behance-line" /></template>
