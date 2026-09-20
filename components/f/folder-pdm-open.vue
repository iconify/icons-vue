<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vphu21bda.css';
import '../../css/q/qcal1ccqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vphu21bda"/><path class="qcal1ccqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-pdm-open" /></template>
