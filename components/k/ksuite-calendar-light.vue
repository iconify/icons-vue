<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_v0fg13q.css';
import '../../css/i/ipzupvdvg.css';
import '../../css/n/nn1z1nbac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r_v0fg13q"/><path class="ipzupvdvg"/><path class="nn1z1nbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-calendar-light" /></template>
