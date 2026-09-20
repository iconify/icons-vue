<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4t0l33wp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x4t0l33wp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:drone-ci-dark" /></template>
