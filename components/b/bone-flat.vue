<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rab22r5bc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="rab22r5bc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:bone-flat" /></template>
