<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7zapnbzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="t7zapnbzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hand-middle-duo" /></template>
