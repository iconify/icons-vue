<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/tof57eb9e.css';
import '../../css/s/shu3xdl9q.css';
import '../../css/a/aqhok2bbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tof57eb9e"/><circle class="shu3xdl9q"/><circle class="aqhok2bbj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:help-line-duotone" /></template>
