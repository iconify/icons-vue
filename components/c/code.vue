<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_5_xsbwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="w_5_xsbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:code" /></template>
