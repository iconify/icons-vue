<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl-740brf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rl-740brf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:drop-dark" /></template>
