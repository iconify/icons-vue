<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcdb8rbbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qcdb8rbbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hugo-light" /></template>
