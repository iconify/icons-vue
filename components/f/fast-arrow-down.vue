<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrul7pbzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrul7pbzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:fast-arrow-down" /></template>
