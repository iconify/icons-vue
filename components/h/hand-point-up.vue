<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssduk0_dj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="ssduk0_dj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hand-point-up" /></template>
