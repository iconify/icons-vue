<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flip2ibmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flip2ibmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:help-circle" /></template>
