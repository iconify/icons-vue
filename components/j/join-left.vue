<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j070gkb1w.css';
import '../../css/x/xi7o5706u.css';
import '../../css/x/x00rglgfe.css';
import '../../css/m/m71q68trp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j070gkb1w"/><path class="xi7o5706u"/><path class="x00rglgfe"/><path class="m71q68trp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:join-left" /></template>
