<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjf68__wr.css';
import '../../css/s/slmsaib5j.css';
import '../../css/x/x0g-2fbkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fjf68__wr"/><path class="slmsaib5j"/><path class="x0g-2fbkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:layers" /></template>
