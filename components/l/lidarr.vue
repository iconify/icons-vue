<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkl81gx0s.css';
import '../../css/e/eevvws5ct.css';
import '../../css/h/hol_21ctj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="nkl81gx0s"/><path class="eevvws5ct"/><path class="hol_21ctj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lidarr" /></template>
