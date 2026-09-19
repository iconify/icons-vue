<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0gu_qbmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0gu_qbmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:abstract" /></template>
