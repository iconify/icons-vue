<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di6nw9_ac.css';
import '../../css/p/pzmzhxbns.css';
import '../../css/x/xcd9w1bsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="di6nw9_ac"/><path class="pzmzhxbns"/><path class="xcd9w1bsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lng-ship-20-bold" /></template>
