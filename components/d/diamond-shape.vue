<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqfc2-b2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="yqfc2-b2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:diamond-shape" /></template>
