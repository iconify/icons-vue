<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzyoycbgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vzyoycbgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:japanese-teacup-and-wifi" /></template>
