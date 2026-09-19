<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl8zptbyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fl8zptbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:cellular" /></template>
