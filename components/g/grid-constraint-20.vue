<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxafyvbuf.css';
import '../../css/t/t7uk038zd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wxafyvbuf"/><path class="t7uk038zd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:grid-constraint-20" /></template>
