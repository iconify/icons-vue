<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sroc94bbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sroc94bbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-left-from-line" /></template>
