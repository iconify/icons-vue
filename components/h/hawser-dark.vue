<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e53pislml.css';
import '../../css/z/zzm1u_hwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e53pislml"/><path class="zzm1u_hwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hawser-dark" /></template>
