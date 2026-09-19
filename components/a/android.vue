<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuj6embez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fuj6embez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:android" /></template>
