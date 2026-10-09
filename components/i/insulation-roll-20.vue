<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpkg76b-y.css';
import '../../css/h/hbmkvs6fl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tpkg76b-y"/><path class="hbmkvs6fl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:insulation-roll-20" /></template>
