<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd8x8dh_y.css';
import '../../css/t/t6iv8tbiq.css';
import '../../css/x/xyg_zebck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kd8x8dh_y"/><path class="t6iv8tbiq"/><path class="xyg_zebck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:hotspot-wave-filled" /></template>
