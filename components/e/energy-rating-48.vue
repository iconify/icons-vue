<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi_kil9dx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mi_kil9dx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:energy-rating-48" /></template>
