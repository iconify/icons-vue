<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avjgpmkfp.css';
import '../../css/d/dd3vljzrf.css';
import '../../css/r/rd9jhd3hp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="avjgpmkfp"/><path class="dd3vljzrf"/><path class="rd9jhd3hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-truck-48-bold" /></template>
