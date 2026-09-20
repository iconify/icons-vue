<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/l4l1k5fea.css';
import '../../css/a/ahz0nysbv.css';
import '../../css/q/q2_ea3wci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l4l1k5fea"/><path class="ahz0nysbv"/><path class="q2_ea3wci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:calendar-upload" /></template>
