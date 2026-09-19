<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmh3annxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="xmh3annxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:at-bold" /></template>
