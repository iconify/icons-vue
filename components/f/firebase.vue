<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3ew7caks.css';
import '../../css/h/hrxhp9b1x.css';
import '../../css/q/qp9ttxbyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e3ew7caks"/><path class="hrxhp9b1x"/><path class="qp9ttxbyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:firebase" /></template>
