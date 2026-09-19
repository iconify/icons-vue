<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx-_r7b2v.css';
import '../../css/v/vam_rybkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tx-_r7b2v"/><path class="vam_rybkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:gradient" /></template>
