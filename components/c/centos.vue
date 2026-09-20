<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuvplbckt.css';
import '../../css/n/n7ffj_asf.css';
import '../../css/c/crzhrw1pi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="vuvplbckt"/><path class="n7ffj_asf"/><path class="crzhrw1pi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:centos" /></template>
