<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d95zj-bto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="d95zj-bto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:battery-empty-1-remix" /></template>
