<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3asime2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3asime2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:globe-arrow-up" /></template>
