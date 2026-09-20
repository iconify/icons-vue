<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqq126x0h.css';
import '../../css/v/vzdg82byd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="aqq126x0h"/><path class="vzdg82byd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:gloves" /></template>
