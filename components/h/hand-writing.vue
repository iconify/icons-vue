<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsnaprmvy.css';
import '../../css/k/kqrt5ob_v.css';
import '../../css/s/s6m-bfbsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bsnaprmvy"/><path class="kqrt5ob_v"/><path class="s6m-bfbsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:hand-writing" /></template>
