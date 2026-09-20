<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4i-kyblv.css';
import '../../css/b/bjt9-ygkq.css';
import '../../css/x/xzmpbzbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o4i-kyblv"/><path class="bjt9-ygkq"/><path class="xzmpbzbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:beauty-mirror-1" /></template>
