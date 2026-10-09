<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_6rndbde.css';
import '../../css/t/ti_1d3blo.css';
import '../../css/k/kew39h_ks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e_6rndbde"/><path class="ti_1d3blo"/><path class="kew39h_ks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flange-48-bold" /></template>
