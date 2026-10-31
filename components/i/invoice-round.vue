<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmc2pd60s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmc2pd60s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:invoice-round" /></template>
