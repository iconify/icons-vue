<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hii-wibir.css';
import '../../css/n/n7h0dab1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hii-wibir"/><path class="n7h0dab1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cpu-48" /></template>
