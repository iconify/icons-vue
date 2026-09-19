<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vail75b-l.css';
import '../../css/t/too86x9zd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vail75b-l"/><path class="too86x9zd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:crop-rotate" /></template>
