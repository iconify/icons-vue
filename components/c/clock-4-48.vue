<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hac57wbhi.css';
import '../../css/h/h2ci1cbmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hac57wbhi"/><path class="h2ci1cbmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:clock-4-48" /></template>
