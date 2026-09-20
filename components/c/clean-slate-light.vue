<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i71hvvbjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i71hvvbjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:clean-slate-light" /></template>
