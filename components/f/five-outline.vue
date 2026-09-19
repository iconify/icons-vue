<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7707_6ks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="x7707_6ks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:five-outline" /></template>
