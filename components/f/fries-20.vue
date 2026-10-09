<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qot8k_bnm.css';
import '../../css/u/uivgpybzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qot8k_bnm"/><path class="uivgpybzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fries-20" /></template>
