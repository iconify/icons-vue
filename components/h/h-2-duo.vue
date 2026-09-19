<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-ow4s4hw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="s-ow4s4hw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:h-2-duo" /></template>
