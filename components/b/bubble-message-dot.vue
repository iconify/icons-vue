<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7e65b99l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="y7e65b99l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:bubble-message-dot" /></template>
