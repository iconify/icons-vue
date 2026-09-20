<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvd31abxp.css';
import '../../css/w/wvhlhkrav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nvd31abxp"/><path class="wvhlhkrav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:bar-chart-h" /></template>
