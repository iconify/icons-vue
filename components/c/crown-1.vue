<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkfnb-b3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="kkfnb-b3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:crown-1" /></template>
