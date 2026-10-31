<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/heb04wnhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="heb04wnhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:link-break-fill-round" /></template>
