<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g60ywcbst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g60ywcbst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:distribute-horizontal-center" /></template>
