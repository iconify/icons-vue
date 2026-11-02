<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qam1p736p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qam1p736p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:follow-line" /></template>
