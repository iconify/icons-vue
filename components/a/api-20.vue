<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq3i9_lhj.css';
import '../../css/y/ydkyucbmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lq3i9_lhj"/><path class="ydkyucbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:api-20" /></template>
