<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eodp9ed2n.css';
import '../../css/r/rfdis-bgk.css';
import '../../css/p/pc88fcihq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eodp9ed2n"/><path class="rfdis-bgk"/><path class="pc88fcihq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:joystick-48" /></template>
