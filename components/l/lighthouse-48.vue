<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh9p_6w5s.css';
import '../../css/y/y2yxtt6_c.css';
import '../../css/l/lhb-r0bja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yh9p_6w5s"/><path class="y2yxtt6_c"/><path class="lhb-r0bja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lighthouse-48" /></template>
