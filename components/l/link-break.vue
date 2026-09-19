<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opoks_fjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="opoks_fjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:link-break" /></template>
