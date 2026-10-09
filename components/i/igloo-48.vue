<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd85o-qpc.css';
import '../../css/l/l4lrodbjn.css';
import '../../css/b/bn5sk2bex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qd85o-qpc"/><path class="l4lrodbjn"/><path class="bn5sk2bex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:igloo-48" /></template>
