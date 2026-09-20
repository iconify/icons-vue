<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3f894b8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q3f894b8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:defibrillator" /></template>
