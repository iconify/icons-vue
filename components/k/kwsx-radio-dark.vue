<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rya8k8jhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rya8k8jhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kwsx-radio-dark" /></template>
