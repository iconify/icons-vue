<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzs4t1bne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzs4t1bne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-network-chart" /></template>
