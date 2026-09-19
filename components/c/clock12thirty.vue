<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt893gged.css';
import '../../css/e/eg39dacou.css';
import '../../css/l/lorjk2lby.css';
import '../../css/e/e--8n0bps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gt893gged"/><path class="eg39dacou"/><path class="lorjk2lby"/><path class="e--8n0bps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:clock12thirty" /></template>
