<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-70ol5nq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="l-70ol5nq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:entertainment-control-button-power-1-power-button-on-off" /></template>
