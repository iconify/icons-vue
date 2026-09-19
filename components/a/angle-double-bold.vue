<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di2q-x_mr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="di2q-x_mr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:angle-double-bold" /></template>
