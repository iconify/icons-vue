<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjp3yo8sn.css';
import '../../css/u/ux9cdwbcv.css';
import '../../css/b/bt0mqnb_p.css';
import '../../css/t/t41k8723w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="fjp3yo8sn"/><path class="ux9cdwbcv"/><path class="bt0mqnb_p"/><path class="t41k8723w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:catalonia" /></template>
