<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h43e48bgp.css';
import '../../css/r/r8v8d6bbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h43e48bgp"/><path class="r8v8d6bbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:electric-boiler-48" /></template>
