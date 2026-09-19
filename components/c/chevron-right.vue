<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czhmj3lqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="czhmj3lqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:chevron-right" /></template>
