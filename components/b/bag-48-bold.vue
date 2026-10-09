<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqivvfbyi.css';
import '../../css/h/hjrxqjbmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aqivvfbyi"/><path class="hjrxqjbmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bag-48-bold" /></template>
