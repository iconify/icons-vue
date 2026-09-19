<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy1vs24lh.css';
import '../../css/k/k3-ivsvyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="sy1vs24lh"/><path class="k3-ivsvyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:gatsby-wordmark" /></template>
