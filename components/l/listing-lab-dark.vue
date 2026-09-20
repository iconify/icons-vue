<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_8qc-bvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g_8qc-bvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:listing-lab-dark" /></template>
