<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9g9dcbtj.css';
import '../../css/l/l45xzzbew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v9g9dcbtj"/><path class="l45xzzbew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flow-battery-48-bold" /></template>
