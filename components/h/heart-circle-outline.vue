<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdhxq_bsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdhxq_bsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:heart-circle-outline" /></template>
