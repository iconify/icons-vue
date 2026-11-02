<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmq_8zrle.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmq_8zrle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:apple-intelligence-frame-line" /></template>
