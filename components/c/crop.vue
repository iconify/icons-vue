<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jywtkxo3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":480};
const content = `<path class="jywtkxo3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:crop" /></template>
