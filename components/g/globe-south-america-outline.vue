<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwlmvlb2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="qwlmvlb2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:globe-south-america-outline" /></template>
