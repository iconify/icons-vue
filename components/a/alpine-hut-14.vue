<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxlm-sbwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="oxlm-sbwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:alpine-hut-14" /></template>
