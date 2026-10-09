<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvx5cvkbp.css';
import '../../css/o/ozmfki5en.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fvx5cvkbp"/><path class="ozmfki5en"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:co2-molecule-48" /></template>
