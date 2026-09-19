<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqa3f49xb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="qqa3f49xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bezier-pentagon" /></template>
