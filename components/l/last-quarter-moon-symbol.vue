<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cftt4jdtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="cftt4jdtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:last-quarter-moon-symbol" /></template>
