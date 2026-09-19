<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cysgz9bwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="cysgz9bwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:hand-index" /></template>
