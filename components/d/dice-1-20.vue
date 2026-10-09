<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxp0_ibgn.css';
import '../../css/w/wg50jyb1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qxp0_ibgn"/><path class="wg50jyb1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dice-1-20" /></template>
