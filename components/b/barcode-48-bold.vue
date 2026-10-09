<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpv1dkbiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hpv1dkbiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:barcode-48-bold" /></template>
