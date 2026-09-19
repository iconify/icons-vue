<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5o9zrbpr.css';
import '../../css/x/xwbchab1b.css';
import '../../css/i/ij1cq3b5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":18,"height":24};
const content = `<path class="d5o9zrbpr"/><path class="xwbchab1b"/><path class="ij1cq3b5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:java" /></template>
