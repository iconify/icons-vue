<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_yur1g1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m_yur1g1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cliparr" /></template>
