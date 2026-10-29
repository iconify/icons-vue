<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/fkfoqunaf.css';
import '../../css/i/i-58-uedr.css';
import '../../css/l/l7ja-xnch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="fkfoqunaf"/><path class="i-58-uedr wm-k"/><path class="l7ja-xnch wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:locate-fixed-sketch" /></template>
