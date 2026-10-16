<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5z7agb-i.css';
import '../../css/l/lrw892zbj.css';
import '../../css/l/l89bje-3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d5z7agb-i"/><path class="lrw892zbj"/><path class="l89bje-3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-trailer-48" /></template>
