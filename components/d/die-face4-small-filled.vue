<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgmu_kbuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="mgmu_kbuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:die-face4-small-filled" /></template>
