<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2w1ue3kd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2304,"height":1280};
const content = `<path class="l2w1ue3kd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:battery-three-quarters" /></template>
