<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn87rsbwd.css';
import '../../css/l/laahlfxkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cn87rsbwd"/><path class="laahlfxkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:immersion-heater-48-bold" /></template>
