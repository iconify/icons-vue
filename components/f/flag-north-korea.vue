<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8cxt48ie.css';
import '../../css/l/ly-2njb2x.css';
import '../../css/f/f35vh31_y.css';
import '../../css/u/u_fw-_buq.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="e8cxt48ie"/><circle class="ly-2njb2x"/><path class="f35vh31_y"/><path class="u_fw-_buq"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:flag-north-korea" /></template>
