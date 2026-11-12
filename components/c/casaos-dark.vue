<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcohwfb8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qcohwfb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:casaos-dark" /></template>
