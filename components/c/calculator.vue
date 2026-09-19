<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq4daq7og.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="qq4daq7og"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:calculator" /></template>
