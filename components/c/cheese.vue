<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmba6gkrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmba6gkrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cheese" /></template>
