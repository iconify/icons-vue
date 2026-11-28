<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kla4l8gus.css';
import '../../css/w/wd9q9w1ik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kla4l8gus secondary"/><path class="primary wd9q9w1ik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:flow-terminator-duo" /></template>
