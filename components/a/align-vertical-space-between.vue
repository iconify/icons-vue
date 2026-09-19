<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twhm25guv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twhm25guv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:align-vertical-space-between" /></template>
