<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz31xb1hd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lz31xb1hd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:funnel-multiple" /></template>
