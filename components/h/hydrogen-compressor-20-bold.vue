<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itjermisk.css';
import '../../css/a/a7tgj93ph.css';
import '../../css/i/ioz9rd6gt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="itjermisk"/><path class="a7tgj93ph"/><path class="ioz9rd6gt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-compressor-20-bold" /></template>
