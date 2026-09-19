<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqps1fqqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="hqps1fqqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hand-middle-bold" /></template>
