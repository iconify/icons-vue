<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhp7qqclq.css';
import '../../css/i/ie_qpyhgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhp7qqclq"/><path class="ie_qpyhgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:chart-network" /></template>
