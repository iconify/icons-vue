<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp69nyjcq.css';
import '../../css/y/yuforsmvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lp69nyjcq"/><path class="yuforsmvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:copy-minus-filled" /></template>
