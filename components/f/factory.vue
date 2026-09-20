<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxhz30baq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="oxhz30baq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:factory" /></template>
