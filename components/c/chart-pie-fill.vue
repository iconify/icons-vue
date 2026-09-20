<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pby7ywbtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pby7ywbtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-pie-fill" /></template>
