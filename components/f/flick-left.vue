<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5q3_ps6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="n5q3_ps6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:flick-left" /></template>
