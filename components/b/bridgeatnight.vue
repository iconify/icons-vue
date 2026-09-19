<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df_1kpbuf.css';
import '../../css/m/m4an1nvxr.css';
import '../../css/s/s9ac_mqsh.css';
import '../../css/f/f1btw72vs.css';
import '../../css/s/sbe6zacnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="df_1kpbuf"/><path class="m4an1nvxr"/><path class="s9ac_mqsh"/><path class="f1btw72vs"/><path class="sbe6zacnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:bridgeatnight" /></template>
