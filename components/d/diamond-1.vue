<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yms31tbmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="yms31tbmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:diamond-1" /></template>
