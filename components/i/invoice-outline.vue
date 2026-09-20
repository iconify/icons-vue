<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxdl1iumf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxdl1iumf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:invoice-outline" /></template>
