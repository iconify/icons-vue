<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp_3l1bkn.css';
import '../../css/b/bf-ekebvc.css';
import '../../css/v/vwtrngb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fp_3l1bkn"/><path class="bf-ekebvc"/><path class="vwtrngb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:light-switch-20-bold" /></template>
