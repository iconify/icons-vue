<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3t59pb3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="t3t59pb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:droplet-bold" /></template>
