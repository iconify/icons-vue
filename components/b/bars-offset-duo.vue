<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gi1p6ucli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="gi1p6ucli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bars-offset-duo" /></template>
