<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5gbubc_q.css';
import '../../css/q/ql7ybibdx.css';
import '../../css/v/vfr8jsk1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="m5gbubc_q"/><circle class="ql7ybibdx"/><path class="vfr8jsk1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:feature-typing" /></template>
