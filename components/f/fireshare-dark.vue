<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpmmq_k7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dpmmq_k7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fireshare-dark" /></template>
