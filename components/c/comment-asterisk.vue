<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev--0sa9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ev--0sa9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:comment-asterisk" /></template>
