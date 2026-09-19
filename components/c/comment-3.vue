<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz_1fupeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="xz_1fupeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:comment-3" /></template>
