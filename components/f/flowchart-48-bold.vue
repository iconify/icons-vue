<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iehgmbc0b.css';
import '../../css/x/x2zs-zbqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iehgmbc0b"/><path class="x2zs-zbqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flowchart-48-bold" /></template>
