<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgvc3bknt.css';
import '../../css/n/nmc_ieezo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tgvc3bknt"/><path class="nmc_ieezo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:graph-bar-vertical-16" /></template>
