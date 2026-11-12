<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5ku-ztwy.css';
import '../../css/i/ib2bxjbcn.css';
import '../../css/m/ma62eabge.css';
import '../../css/a/aqp8o2-2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q5ku-ztwy"/><path class="ib2bxjbcn"/><path class="ma62eabge"/><path class="aqp8o2-2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:homescreen-hero-dark" /></template>
