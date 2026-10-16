<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qst8sacvr.css';
import '../../css/n/ncpk28ife.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qst8sacvr"/><path class="ncpk28ife"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dosimeter-48" /></template>
