<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsdri7q7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsdri7q7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:apple-intelligence-line" /></template>
