<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_dnl3bgj.css';
import '../../css/o/ote0d1bdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_dnl3bgj"/><path class="ote0d1bdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:coqui" /></template>
