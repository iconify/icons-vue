<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzjt250kh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzjt250kh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:currency-dollar-fill-round" /></template>
