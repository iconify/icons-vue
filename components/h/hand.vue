<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xinez6ctk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="xinez6ctk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:hand" /></template>
