<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohpbt_2nc.css';
import '../../css/h/h5dbk_bhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ohpbt_2nc"/><path class="h5dbk_bhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fish-48" /></template>
