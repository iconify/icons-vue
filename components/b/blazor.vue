<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je1a2q5xr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="je1a2q5xr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:blazor" /></template>
