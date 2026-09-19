<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsyyj6buq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<rect transform="rotate(45 40 12)" class="dsyyj6buq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:diamond-1-duo" /></template>
