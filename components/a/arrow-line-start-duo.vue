<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t87l6hbgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="t87l6hbgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:arrow-line-start-duo" /></template>
