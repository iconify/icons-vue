<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz_4v-slc.css';
import '../../css/t/tebjm8_ui.css';
import '../../css/i/i4kmshdkq.css';
import '../../css/p/pxs_36bfv.css';
import '../../css/y/yg1ho1_sl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="vz_4v-slc"/><path class="tebjm8_ui"/><path class="i4kmshdkq"/><path class="pxs_36bfv"/><path class="yg1ho1_sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:libya" /></template>
