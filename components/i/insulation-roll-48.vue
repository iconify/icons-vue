<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw2u6puwh.css';
import '../../css/r/r_oqf1inc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yw2u6puwh"/><path class="r_oqf1inc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:insulation-roll-48" /></template>
