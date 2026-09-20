<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6-qsdc1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6-qsdc1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:h-6" /></template>
