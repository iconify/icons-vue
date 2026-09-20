<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5nrp29qc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="w5nrp29qc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:checkered-flag-on-flag-handle" /></template>
