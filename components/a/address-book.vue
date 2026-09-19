<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t68u_vbpr.css';
import '../../css/c/cs3fob1lr.css';
import '../../css/w/wfz41fcby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t68u_vbpr"/><path class="cs3fob1lr"/><path class="wfz41fcby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:address-book" /></template>
