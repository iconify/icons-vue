<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntevb2ahc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntevb2ahc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dashboard-4-line" /></template>
