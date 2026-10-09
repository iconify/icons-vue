<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjzrwdbzw.css';
import '../../css/g/gac0p61ax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hjzrwdbzw"/><path class="gac0p61ax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bell-off-48-bold" /></template>
