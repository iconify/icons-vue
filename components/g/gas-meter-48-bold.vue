<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df474cc-n.css';
import '../../css/y/yxgyrcb-d.css';
import '../../css/r/rkg9se97n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="df474cc-n"/><path class="yxgyrcb-d"/><path class="rkg9se97n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gas-meter-48-bold" /></template>
