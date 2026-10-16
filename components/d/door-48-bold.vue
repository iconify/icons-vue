<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9f-pebyy.css';
import '../../css/a/aaw7kqsgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m9f-pebyy"/><path class="aaw7kqsgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:door-48-bold" /></template>
