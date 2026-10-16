<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsmhpgwcs.css';
import '../../css/f/fc_5vwb2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tsmhpgwcs"/><path class="fc_5vwb2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:aspect-ratio-48" /></template>
