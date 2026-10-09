<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfspippzt.css';
import '../../css/q/qkvjsbbnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vfspippzt"/><path class="qkvjsbbnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hex-nut-48-bold" /></template>
