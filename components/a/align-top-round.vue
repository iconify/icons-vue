<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdo2xjb2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdo2xjb2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:align-top-round" /></template>
