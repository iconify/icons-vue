<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8n2l28xw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8n2l28xw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:check-duo" /></template>
