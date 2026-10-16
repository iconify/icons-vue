<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2k8ah5hs.css';
import '../../css/q/q18-obcpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d2k8ah5hs"/><path class="q18-obcpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:alarm-clock-off-48-bold" /></template>
