<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyzk63bam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fyzk63bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:currency-btc" /></template>
