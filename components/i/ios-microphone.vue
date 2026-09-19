<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm6g_lhrv.css';
import '../../css/d/dgu1br39e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nm6g_lhrv"/><path class="dgu1br39e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-microphone" /></template>
