<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmrqvr5kr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="jmrqvr5kr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:four-bold" /></template>
