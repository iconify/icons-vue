<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yolrx-bvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yolrx-bvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-gemini-light" /></template>
