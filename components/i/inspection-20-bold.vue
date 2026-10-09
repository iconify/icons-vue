<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz7gt-bls.css';
import '../../css/f/fga2-cbvt.css';
import '../../css/n/n8zhxcbkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yz7gt-bls"/><path class="fga2-cbvt"/><path class="n8zhxcbkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:inspection-20-bold" /></template>
