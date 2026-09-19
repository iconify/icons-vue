<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsipz1bfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="wsipz1bfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:comment-exclamation" /></template>
