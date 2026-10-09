<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgy1l_tlx.css';
import '../../css/n/nx7dqhb3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hgy1l_tlx"/><path class="nx7dqhb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-right-20-bold" /></template>
