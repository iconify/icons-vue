<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m35bpgbdz.css';
import '../../css/h/hywj0nnlp.css';
import '../../css/d/ddyvihbls.css';
import '../../css/x/xcawsdbae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m35bpgbdz"/><path class="hywj0nnlp"/><path class="ddyvihbls"/><path class="xcawsdbae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:bookmarktab" /></template>
