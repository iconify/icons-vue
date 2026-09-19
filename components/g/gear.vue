<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dccl6cslv.css';
import '../../css/a/a0a43bbqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="dccl6cslv"/><path class="a0a43bbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:gear" /></template>
