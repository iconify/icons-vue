<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/kr4evflrk.css';
import '../../css/j/jdzoki6fy.css';
import '../../css/s/s7et_6b9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kr4evflrk"/><path class="jdzoki6fy"/><path class="s7et_6b9q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dialog-line-duotone" /></template>
