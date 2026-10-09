<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvtyb5b6l.css';
import '../../css/a/a_35o2j3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hvtyb5b6l"/><path class="a_35o2j3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-sankey-48" /></template>
