<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbk4vsmtj.css';
import '../../css/w/ww_xydb2s.css';
import '../../css/e/ejdsdgbzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qbk4vsmtj"/><path class="ww_xydb2s"/><path class="ejdsdgbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:drum-48" /></template>
