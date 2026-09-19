<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_bsnpbbl.css';
import '../../css/j/j7f3w3rlj.css';
import '../../css/s/sdf8cb9as.css';
import '../../css/a/arfms3bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="h_bsnpbbl"/><circle class="j7f3w3rlj"/><circle class="sdf8cb9as"/><path class="arfms3bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:intent-request-inactive" /></template>
