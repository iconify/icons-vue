<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5l2hstxs.css';
import '../../css/y/yub7c6b0d.css';
import '../../css/g/g6wu-497r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q5l2hstxs"/><path class="yub7c6b0d"/><path class="g6wu-497r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:earth-layers-20" /></template>
