<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khylky-1c.css';
import '../../css/t/t-6ze0bzb.css';
import '../../css/n/non-6ivtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="khylky-1c"/><path class="t-6ze0bzb"/><path class="non-6ivtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fire-alarm-20" /></template>
