<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qelgfsblo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qelgfsblo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:direction-rotary-right" /></template>
