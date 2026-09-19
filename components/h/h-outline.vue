<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmz29g4sa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="jmz29g4sa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:h-outline" /></template>
