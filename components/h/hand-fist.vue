<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnjp8ib7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="xnjp8ib7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:hand-fist" /></template>
