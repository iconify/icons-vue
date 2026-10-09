<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozhwhlihc.css';
import '../../css/k/kr4l01btv.css';
import '../../css/n/nrn-6ibeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ozhwhlihc"/><path class="kr4l01btv"/><path class="nrn-6ibeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lamp-20" /></template>
