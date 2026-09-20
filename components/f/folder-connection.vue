<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd1yx_bjk.css';
import '../../css/q/qu-z_obdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kd1yx_bjk"/><path class="qu-z_obdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-connection" /></template>
