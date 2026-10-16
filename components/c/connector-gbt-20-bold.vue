<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0oa-qzdz.css';
import '../../css/e/ef1ws3b1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c0oa-qzdz"/><path class="ef1ws3b1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:connector-gbt-20-bold" /></template>
