<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6njav50m.css';
import '../../css/o/oljydkxyh.css';
import '../../css/x/xoyjgxgiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p6njav50m"/><path class="oljydkxyh"/><path class="xoyjgxgiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charger-slow-20" /></template>
