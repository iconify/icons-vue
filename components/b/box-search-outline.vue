<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv3t5fpaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hv3t5fpaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:box-search-outline" /></template>
