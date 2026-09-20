<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa-vvbzgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oa-vvbzgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:face-sad" /></template>
