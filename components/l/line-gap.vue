<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mplgb07ei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="mplgb07ei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:line-gap" /></template>
