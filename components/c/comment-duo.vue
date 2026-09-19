<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szs2yjbrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="szs2yjbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:comment-duo" /></template>
