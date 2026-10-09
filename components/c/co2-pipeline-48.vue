<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oaq0blbdk.css';
import '../../css/p/ppdr4b5kz.css';
import '../../css/y/y7x0imbpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oaq0blbdk"/><path class="ppdr4b5kz"/><path class="y7x0imbpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:co2-pipeline-48" /></template>
