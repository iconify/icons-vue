<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6h-m2bpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6h-m2bpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:letter-r-box-outline" /></template>
