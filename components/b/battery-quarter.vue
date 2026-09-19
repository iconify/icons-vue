<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1m_r6_oj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="l1m_r6_oj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:battery-quarter" /></template>
