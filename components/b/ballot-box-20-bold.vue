<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufl2bny3v.css';
import '../../css/e/eay9adclz.css';
import '../../css/t/tf2yhvbfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ufl2bny3v"/><path class="eay9adclz"/><path class="tf2yhvbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ballot-box-20-bold" /></template>
