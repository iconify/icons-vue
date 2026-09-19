<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i27jy566b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="i27jy566b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:activity-1" /></template>
