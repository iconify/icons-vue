<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzit4obey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="yzit4obey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:arrow-line-end-outline" /></template>
