<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vo3r_qbrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vo3r_qbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:duckdns" /></template>
