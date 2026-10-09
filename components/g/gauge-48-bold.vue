<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_q60hbmc.css';
import '../../css/v/vlw_01baz.css';
import '../../css/g/gxf5i4yhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i_q60hbmc"/><path class="vlw_01baz"/><path class="gxf5i4yhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gauge-48-bold" /></template>
