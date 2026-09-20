<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn7xlvr2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="xn7xlvr2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:cctv" /></template>
