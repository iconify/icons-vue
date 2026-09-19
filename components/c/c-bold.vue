<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1phebb2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="x1phebb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:c-bold" /></template>
