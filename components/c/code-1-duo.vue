<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yq8q-ltfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="yq8q-ltfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:code-1-duo" /></template>
