<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tuhs32-ml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="tuhs32-ml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:cycling" /></template>
