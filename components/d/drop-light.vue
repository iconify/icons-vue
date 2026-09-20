<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zniae-8kh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zniae-8kh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:drop-light" /></template>
