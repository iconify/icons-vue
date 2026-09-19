<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsm13zbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="lsm13zbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:ampersand-2-duo" /></template>
