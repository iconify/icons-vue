<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb7q07bxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="cb7q07bxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:calendar" /></template>
