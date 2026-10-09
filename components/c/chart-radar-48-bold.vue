<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnz38bbup.css';
import '../../css/x/x-e0pwbux.css';
import '../../css/m/msg7k8bbh.css';
import '../../css/w/wyuzfgbum.css';
import '../../css/o/oemkp8bpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mnz38bbup"/><path class="x-e0pwbux"/><path class="msg7k8bbh"/><path class="wyuzfgbum"/><path class="oemkp8bpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-radar-48-bold" /></template>
