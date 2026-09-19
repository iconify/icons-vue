<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/roweh2vhe.css';
import '../../css/q/qq-quxyif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="roweh2vhe"/><path class="qq-quxyif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:import" /></template>
