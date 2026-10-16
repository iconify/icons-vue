<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpapdbc8v.css';
import '../../css/y/yeva_mbnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lpapdbc8v"/><path class="yeva_mbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:immersion-heater-48" /></template>
