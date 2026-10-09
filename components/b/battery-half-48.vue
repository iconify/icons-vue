<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elpovvbol.css';
import '../../css/o/oc56z-biv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="elpovvbol"/><path class="oc56z-biv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-half-48" /></template>
