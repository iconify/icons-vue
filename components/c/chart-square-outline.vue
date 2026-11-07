<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-l_t8zlt.css';
import '../../css/e/e-_t4f13s.css';
import '../../css/t/tf373tbqk.css';
import '../../css/t/t5k-_f5ou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-l_t8zlt"/><path class="e-_t4f13s"/><path class="tf373tbqk"/><path clip-rule="evenodd" class="t5k-_f5ou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chart-square-outline" /></template>
