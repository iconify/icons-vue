<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztgw17b4p.css';
import '../../css/l/laiy7fbkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="ztgw17b4p"/><path class="laiy7fbkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:chart-increasing-with-yen" /></template>
