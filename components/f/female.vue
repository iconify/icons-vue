<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh1vwnbpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="nh1vwnbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:female" /></template>
