<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbbjbl9yn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="tbbjbl9yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:kiss-beam-bold" /></template>
