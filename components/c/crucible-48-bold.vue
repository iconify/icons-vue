<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/laierucpu.css';
import '../../css/y/y_bkliy_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="laierucpu"/><path class="y_bkliy_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crucible-48-bold" /></template>
