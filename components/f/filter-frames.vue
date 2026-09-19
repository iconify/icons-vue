<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_tr_7bxk.css';
import '../../css/q/qks_3bc-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w_tr_7bxk"/><path class="qks_3bc-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:filter-frames" /></template>
