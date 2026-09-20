<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkkkvn-jc.css';
import '../../css/v/vnaypctab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dkkkvn-jc"/><path class="vnaypctab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:change-clean-energy" /></template>
