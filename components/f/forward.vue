<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrradhcvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1568,"height":1536};
const content = `<g transform="translate(1568 0) scale(-1 1)"><path class="qrradhcvv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:forward" /></template>
