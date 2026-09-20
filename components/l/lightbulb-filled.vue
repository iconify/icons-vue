<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipv-8xbrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipv-8xbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:lightbulb-filled" /></template>
