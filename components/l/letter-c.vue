<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi2x7ybxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mi2x7ybxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:letter-c" /></template>
