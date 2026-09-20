<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3ti-bn3p.css';
import '../../css/g/gjagohdeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="i3ti-bn3p"/><path class="gjagohdeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:calendar" /></template>
