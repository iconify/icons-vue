<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qaku_ef4i.css';
import '../../css/r/rk8kk9b0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qaku_ef4i"/><path class="rk8kk9b0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:fire" /></template>
