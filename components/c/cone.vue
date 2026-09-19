<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7tj8ibcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="c7tj8ibcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:cone" /></template>
