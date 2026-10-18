<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p270hkbyv.css';
import '../../css/l/l9etfhdic.css';
import '../../css/r/r1ehujbqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p270hkbyv"/><path class="l9etfhdic"/><path class="r1ehujbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ground-mount-48" /></template>
