<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl5uzhbhz.css';
import '../../css/d/d3wfw4b1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vl5uzhbhz wm-k"/><path class="d3wfw4b1i wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:info-circle" /></template>
