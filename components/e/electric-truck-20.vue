<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm0dtlbqb.css';
import '../../css/k/ko9a2zbln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hm0dtlbqb"/><path class="ko9a2zbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:electric-truck-20" /></template>
