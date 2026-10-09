<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_d-chbfv.css';
import '../../css/p/p48t35bio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r_d-chbfv"/><path class="p48t35bio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:connector-type2-20" /></template>
