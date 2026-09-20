<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc4cu_bam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wc4cu_bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:librewolf" /></template>
