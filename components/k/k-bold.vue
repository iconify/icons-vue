<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t544ezb-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="t544ezb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:k-bold" /></template>
