<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzew16btg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="vzew16btg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:heading" /></template>
