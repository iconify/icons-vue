<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl7c8kphf.css';
import '../../css/j/ja_pkqero.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tl7c8kphf"/><path class="ja_pkqero"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:car-front" /></template>
