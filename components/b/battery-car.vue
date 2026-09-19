<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5umrybpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="p5umrybpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:battery-car" /></template>
