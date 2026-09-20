<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kp195kbkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kp195kbkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:clean-slate-dark" /></template>
