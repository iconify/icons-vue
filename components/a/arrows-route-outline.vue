<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl1s8xrfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="xl1s8xrfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:arrows-route-outline" /></template>
