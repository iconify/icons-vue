<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icit6mbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="icit6mbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:bubble-message-hi" /></template>
