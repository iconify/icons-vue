<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6xg2yb8p.css';
import '../../css/k/k86_pzbaj.css';
import '../../css/p/pokp4-yvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w6xg2yb8p"/><path class="k86_pzbaj"/><path class="pokp4-yvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:drone-inspection-48" /></template>
