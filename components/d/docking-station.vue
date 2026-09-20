<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yry6u38_x.css';
import '../../css/v/vci34obyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yry6u38_x"/><path class="vci34obyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:docking-station" /></template>
