<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knx2mmctr.css';
import '../../css/g/g8p6evbep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="knx2mmctr"/><path class="g8p6evbep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:deforestation-20" /></template>
