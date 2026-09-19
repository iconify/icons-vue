<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2p2k_glq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m2p2k_glq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:ballottscriptx" /></template>
