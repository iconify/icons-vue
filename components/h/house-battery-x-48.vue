<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajch12nad.css';
import '../../css/p/pi81u0bva.css';
import '../../css/x/x_6yldbeu.css';
import '../../css/b/bdkl8-dne.css';
import '../../css/j/j3cy-fbyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ajch12nad"/><path class="pi81u0bva"/><path class="x_6yldbeu"/><path class="bdkl8-dne"/><path class="j3cy-fbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-battery-x-48" /></template>
