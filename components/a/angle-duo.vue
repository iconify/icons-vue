<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n14n-3bio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="n14n-3bio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:angle-duo" /></template>
