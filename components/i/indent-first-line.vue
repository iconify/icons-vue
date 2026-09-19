<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2x2vid8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="q2x2vid8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:indent-first-line" /></template>
