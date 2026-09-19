<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwl_jabpn.css';
import '../../css/j/jxfvkgb2p.css';
import '../../css/y/ybddlyukq.css';
import '../../css/r/rmx2knb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cwl_jabpn"/><path class="jxfvkgb2p"/><path class="ybddlyukq"/><path class="rmx2knb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:hammer" /></template>
