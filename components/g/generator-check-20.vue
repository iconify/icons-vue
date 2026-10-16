<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le62_1bgw.css';
import '../../css/w/wikar0bxx.css';
import '../../css/q/qh3-d7bck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="le62_1bgw"/><path class="wikar0bxx"/><path class="qh3-d7bck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:generator-check-20" /></template>
