<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opnuv-atr.css';
import '../../css/q/qirndk33c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="opnuv-atr"/><path class="qirndk33c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-timer" /></template>
