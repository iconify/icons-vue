<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx4291bta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="hx4291bta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:border-none-duo" /></template>
