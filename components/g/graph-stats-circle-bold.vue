<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsrkrvcpu.css';
import '../../css/u/uv8ih1bxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jsrkrvcpu"/><path class="uv8ih1bxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:graph-stats-circle-bold" /></template>
