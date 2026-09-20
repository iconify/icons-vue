<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o51_pm-7x.css';
import '../../css/y/ydjw7j4fv.css';
import '../../css/r/r0wa9gb5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o51_pm-7x"/><path class="ydjw7j4fv"/><path class="r0wa9gb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gryt-dark" /></template>
