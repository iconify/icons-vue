<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot_iz2bwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":704,"height":1000};
const content = `<path class="ot_iz2bwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="brandico:box" /></template>
