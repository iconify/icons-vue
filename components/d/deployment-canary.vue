<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-s-y5s8p.css';
import '../../css/w/w_-ne2bhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="u-s-y5s8p"/><path class="w_-ne2bhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:deployment-canary" /></template>
