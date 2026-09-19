<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6zmjje5d.css';
import '../../css/y/yr811vbtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u6zmjje5d"/><path class="yr811vbtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:keyboard" /></template>
