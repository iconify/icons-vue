<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovjgg_gxh.css';
import '../../css/p/psfb6tk7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ouiIcon__fillSecondary ovjgg_gxh"/><path class="psfb6tk7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:app-auditbeat" /></template>
