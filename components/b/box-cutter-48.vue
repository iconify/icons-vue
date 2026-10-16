<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc3ilob8v.css';
import '../../css/o/ocwmt_j3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oc3ilob8v"/><path class="ocwmt_j3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:box-cutter-48" /></template>
