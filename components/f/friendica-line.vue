<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggcbnvb2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggcbnvb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:friendica-line" /></template>
