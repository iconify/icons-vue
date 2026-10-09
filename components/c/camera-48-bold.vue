<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdrt4wkoq.css';
import '../../css/i/iwhux3djk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hdrt4wkoq"/><path class="iwhux3djk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:camera-48-bold" /></template>
