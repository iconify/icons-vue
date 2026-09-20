<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idsu3yboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="idsu3yboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-bar-chart-horizontal-end-fill" /></template>
