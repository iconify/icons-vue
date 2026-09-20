<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytvaq_byd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ytvaq_byd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gopeed-light" /></template>
