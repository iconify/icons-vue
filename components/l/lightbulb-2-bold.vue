<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebp_wrb2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ebp_wrb2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:lightbulb-2-bold" /></template>
