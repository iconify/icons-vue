<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlsrljbwz.css';
import '../../css/c/cdtctobwy.css';
import '../../css/s/spr4jhb3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rlsrljbwz"/><path class="cdtctobwy"/><path class="spr4jhb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cybersecurity-48" /></template>
