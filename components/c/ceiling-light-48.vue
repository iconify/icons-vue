<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2spr2bve.css';
import '../../css/x/xlfcvcr0c.css';
import '../../css/q/q7ailzblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f2spr2bve"/><path class="xlfcvcr0c"/><path class="q7ailzblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ceiling-light-48" /></template>
