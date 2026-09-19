<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xldwc8vhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="xldwc8vhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:align-side" /></template>
