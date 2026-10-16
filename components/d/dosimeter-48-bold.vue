<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8d9-acuv.css';
import '../../css/t/t3nsxqbji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k8d9-acuv"/><path class="t3nsxqbji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dosimeter-48-bold" /></template>
