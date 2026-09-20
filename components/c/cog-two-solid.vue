<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjva_kt4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjva_kt4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cog-two-solid" /></template>
