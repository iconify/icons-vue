<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn313-bdo.css';
import '../../css/c/cw3ksvblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fn313-bdo"/><path class="cw3ksvblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:landfill-gas-48" /></template>
