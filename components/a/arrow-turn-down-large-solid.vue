<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhv3jp_gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fhv3jp_gm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:arrow-turn-down-large-solid" /></template>
