<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iswl_3bic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iswl_3bic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-network-chart" /></template>
