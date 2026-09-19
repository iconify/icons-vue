<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1nqy3byq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="p1nqy3byq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:cursor-duo" /></template>
