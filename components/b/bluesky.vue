<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_q6p6bet.css';
import '../../css/v/vo_do-qpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="d_q6p6bet"/><path class="vo_do-qpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:bluesky" /></template>
