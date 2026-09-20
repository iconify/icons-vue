<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzxl6r1_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qzxl6r1_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kiroshi-dark" /></template>
