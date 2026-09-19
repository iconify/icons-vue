<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0o2q1bsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="s0o2q1bsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:arrow-left" /></template>
