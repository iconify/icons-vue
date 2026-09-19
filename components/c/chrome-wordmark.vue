<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr272q-zt.css';
import '../../css/m/mhc-hp51p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<circle class="wr272q-zt"/><path class="mhc-hp51p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:chrome-wordmark" /></template>
