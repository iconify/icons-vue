<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t40t0mbhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="t40t0mbhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:chevron-bold" /></template>
