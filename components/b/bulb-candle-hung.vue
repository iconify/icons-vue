<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsasowb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsasowb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bulb-candle-hung" /></template>
