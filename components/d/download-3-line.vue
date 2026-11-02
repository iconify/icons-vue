<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvs-sobwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvs-sobwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:download-3-line" /></template>
