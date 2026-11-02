<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk121vbgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wk121vbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:between-horizontal-end-line" /></template>
