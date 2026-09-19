<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qthw8xbzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qthw8xbzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:fishing-area-2" /></template>
