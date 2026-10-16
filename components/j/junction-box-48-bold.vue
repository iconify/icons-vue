<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrn60viue.css';
import '../../css/f/fvyubxb-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hrn60viue"/><path class="fvyubxb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:junction-box-48-bold" /></template>
