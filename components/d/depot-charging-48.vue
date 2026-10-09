<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt3wdaccl.css';
import '../../css/d/d7a8hbbiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tt3wdaccl"/><path class="d7a8hbbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:depot-charging-48" /></template>
