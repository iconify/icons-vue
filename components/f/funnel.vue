<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp939ybwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lp939ybwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:funnel" /></template>
