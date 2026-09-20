<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vddm3wbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="vddm3wbri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:flip-horizontal-circle-2" /></template>
