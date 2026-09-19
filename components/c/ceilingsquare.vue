<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy8fiyi9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fy8fiyi9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ceilingsquare" /></template>
