<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oum63jbgm.css';
import '../../css/d/dg95q9b0l.css';
import '../../css/g/g7b-z_b_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oum63jbgm"/><path class="dg95q9b0l"/><path class="g7b-z_b_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flywheel-48-bold" /></template>
