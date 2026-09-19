<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xvgdg2apg.css';
import '../../css/i/ikqvnnbxe.css';
import '../../css/c/co27a8zen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="xvgdg2apg"/><circle class="ikqvnnbxe"/><path class="co27a8zen"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:blade" /></template>
