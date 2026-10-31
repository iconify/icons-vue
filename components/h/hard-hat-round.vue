<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n65np6ypu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n65np6ypu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hard-hat-round" /></template>
