<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wn1r1dbvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="wn1r1dbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:d-pad-bold" /></template>
