<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv63tfbxq.css';
import '../../css/f/fi_q4_r5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bv63tfbxq"/><path class="fi_q4_r5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:flow-logs-vpc" /></template>
