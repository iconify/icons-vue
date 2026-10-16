<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-rt1kbiq.css';
import '../../css/m/msqhepy4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f-rt1kbiq"/><path class="msqhepy4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:delivery-robot-48" /></template>
