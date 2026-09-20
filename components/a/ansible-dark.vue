<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjbp16bqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gjbp16bqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ansible-dark" /></template>
