<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r263ow21w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r263ow21w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:level-one-rtl" /></template>
