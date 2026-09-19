<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vf52vtinf.css';
import '../../css/r/rsmyz1hsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vf52vtinf"/><path class="rsmyz1hsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-event-streams" /></template>
