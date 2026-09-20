<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldpv-hf5n.css';
import '../../css/y/yg0jyhbej.css';
import '../../css/h/hba5kpbit.css';
import '../../css/n/nn551pqdp.css';
import '../../css/y/yu8pyjesp.css';
import '../../css/x/xl-g2xt0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ldpv-hf5n"/><path class="yg0jyhbej"/><path class="hba5kpbit"/><path class="nn551pqdp"/><path class="yu8pyjesp"/><path class="xl-g2xt0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-drive" /></template>
