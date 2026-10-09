<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpn7eesli.css';
import '../../css/v/v_25zwbbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mpn7eesli"/><path class="v_25zwbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-container-20" /></template>
