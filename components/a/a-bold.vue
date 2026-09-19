<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwemtzb2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="xwemtzb2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:a-bold" /></template>
