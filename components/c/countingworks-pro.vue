<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eaqvalh9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eaqvalh9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:countingworks-pro" /></template>
