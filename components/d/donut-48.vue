<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hac57wbhi.css';
import '../../css/o/os-c1macg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hac57wbhi"/><path class="os-c1macg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:donut-48" /></template>
