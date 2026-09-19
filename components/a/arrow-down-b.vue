<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_uy_9btj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f_uy_9btj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:arrow-down-b" /></template>
