<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w006lobzc.css';
import '../../css/t/tx2rzib1i.css';
import '../../css/d/d-m49pkha.css';
import '../../css/x/xmfwdpb2z.css';
import '../../css/f/f75-xob9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w006lobzc"/><path class="tx2rzib1i"/><path class="d-m49pkha"/><path class="xmfwdpb2z"/><path class="f75-xob9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jupyter" /></template>
