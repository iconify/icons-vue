<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_c-jfbdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="z_c-jfbdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:g-duo" /></template>
