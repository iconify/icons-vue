<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0ryvgb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="i0ryvgb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hand-peace-duo" /></template>
