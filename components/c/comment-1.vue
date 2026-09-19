<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp8queyss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="yp8queyss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:comment-1" /></template>
