<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhjziobee.css';
import '../../css/o/oywhc6eaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qhjziobee"/><path class="oywhc6eaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:female" /></template>
