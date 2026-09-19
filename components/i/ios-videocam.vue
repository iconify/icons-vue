<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drmjsqkyz.css';
import '../../css/r/rab5k-b0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="drmjsqkyz"/><path class="rab5k-b0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-videocam" /></template>
