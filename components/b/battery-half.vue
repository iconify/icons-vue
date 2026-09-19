<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubpd-wbmq.css';
import '../../css/q/qfztaod5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ubpd-wbmq"/><path class="qfztaod5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:battery-half" /></template>
