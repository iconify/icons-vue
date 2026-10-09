<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-pj1ullj.css';
import '../../css/v/vfwj5rb6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l-pj1ullj"/><path class="vfwj5rb6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:calculator-48-bold" /></template>
