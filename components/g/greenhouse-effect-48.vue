<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzwpf0b4o.css';
import '../../css/e/em99sdy4o.css';
import '../../css/t/t_pv4sbxm.css';
import '../../css/l/l-tauacug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kzwpf0b4o"/><path class="em99sdy4o"/><path class="t_pv4sbxm"/><path class="l-tauacug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:greenhouse-effect-48" /></template>
