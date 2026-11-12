<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1m_q4b0x.css';
import '../../css/w/wfa-59b9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v1m_q4b0x"/><path class="wfa-59b9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:flow-like-dark" /></template>
