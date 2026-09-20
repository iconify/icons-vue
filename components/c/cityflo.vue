<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwh12uzbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":192,"height":61};
const content = `<path class="rwh12uzbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cityflo" /></template>
