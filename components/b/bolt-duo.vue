<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrxkjsb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="rrxkjsb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bolt-duo" /></template>
