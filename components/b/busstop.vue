<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ficd_6bue.css';
import '../../css/o/oqza4fg4m.css';
import '../../css/m/mt_s06c5k.css';
import '../../css/m/m7jr4ydoi.css';
import '../../css/f/fe8myiixm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ficd_6bue"/><path class="oqza4fg4m"/><circle class="mt_s06c5k"/><path class="m7jr4ydoi"/><path class="fe8myiixm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:busstop" /></template>
