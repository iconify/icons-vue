<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxfwt4bzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="pxfwt4bzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:angle" /></template>
