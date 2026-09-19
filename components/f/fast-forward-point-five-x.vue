<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrv_3ebjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qrv_3ebjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:fast-forward-point-five-x" /></template>
