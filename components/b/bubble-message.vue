<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg3dhfb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="xg3dhfb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:bubble-message" /></template>
