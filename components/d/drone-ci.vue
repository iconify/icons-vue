<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqoty1doq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mqoty1doq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:drone-ci" /></template>
