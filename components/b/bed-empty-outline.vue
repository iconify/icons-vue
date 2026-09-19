<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgpee-b0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="tgpee-b0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bed-empty-outline" /></template>
