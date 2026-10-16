<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/seho2dbyy.css';
import '../../css/w/wmbs3e3ue.css';
import '../../css/g/gikfybcho.css';
import '../../css/j/jc-p_wbxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="seho2dbyy"/><path class="wmbs3e3ue"/><path class="gikfybcho"/><path class="jc-p_wbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:electric-heater-48-bold" /></template>
