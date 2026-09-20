<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-g1_5bam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s-g1_5bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:loading-horizontal-2" /></template>
