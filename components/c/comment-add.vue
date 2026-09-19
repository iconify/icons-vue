<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtlmarb7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="gtlmarb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:comment-add" /></template>
