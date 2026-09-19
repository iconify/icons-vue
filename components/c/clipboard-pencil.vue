<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2auhh-bp.css';
import '../../css/v/vwi05mrad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="a2auhh-bp"/><path class="vwi05mrad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:clipboard-pencil" /></template>
