<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd_096brd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="jd_096brd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:googleplus" /></template>
