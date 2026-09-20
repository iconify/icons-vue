<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mmtdotb0s.css';
import '../../css/l/lsyzzy5ql.css';
import '../../css/l/l3a7hfkmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mmtdotb0s"/><circle class="lsyzzy5ql"/><path class="l3a7hfkmc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-chrome" /></template>
