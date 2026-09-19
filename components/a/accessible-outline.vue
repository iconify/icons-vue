<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig9f87b2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ig9f87b2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:accessible-outline" /></template>
