<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rff7kwx6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rff7kwx6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:e-trade-dark" /></template>
