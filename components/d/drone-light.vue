<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx937tb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":230,"height":230};
const content = `<path class="xx937tb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:drone-light" /></template>
