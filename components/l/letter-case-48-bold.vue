<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nuumlzbuz.css';
import '../../css/s/so4buhb_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nuumlzbuz"/><path class="so4buhb_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:letter-case-48-bold" /></template>
