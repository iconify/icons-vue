<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4uuy_b9u.css';
import '../../css/l/lq6x1topr.css';
import '../../css/h/hcihy2b2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t4uuy_b9u"/><path class="lq6x1topr"/><path class="hcihy2b2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:co2-ship-48" /></template>
