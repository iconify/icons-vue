<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wiwu_wund.css';
import '../../css/g/g714mx3oh.css';
import '../../css/i/iufs412sl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wiwu_wund"/><path class="g714mx3oh"/><path class="iufs412sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:finn-dark" /></template>
