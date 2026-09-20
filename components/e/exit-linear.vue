<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/into8ac1h.css';
import '../../css/e/ezshh0bgn.css';
import '../../css/l/luu53hbat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="into8ac1h"/><path class="ezshh0bgn"/><path class="luu53hbat"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:exit-linear" /></template>
