<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbi8q-fnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="vbi8q-fnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:arrow-turn" /></template>
