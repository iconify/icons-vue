<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa81hmtbv.css';
import '../../css/i/ik6s6dbfj.css';
import '../../css/n/n3iczmbsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aa81hmtbv"/><path class="ik6s6dbfj"/><path class="n3iczmbsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:airport-48-bold" /></template>
