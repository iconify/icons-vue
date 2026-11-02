<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za0ygy1bp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="za0ygy1bp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:grid-2x2-x-fill" /></template>
