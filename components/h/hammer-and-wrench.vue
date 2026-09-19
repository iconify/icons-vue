<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp2chbbkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qp2chbbkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:hammer-and-wrench" /></template>
