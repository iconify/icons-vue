<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuhv4polx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="fuhv4polx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:at" /></template>
