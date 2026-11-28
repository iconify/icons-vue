<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j51u2ccon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j51u2ccon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:ambulance-alert" /></template>
