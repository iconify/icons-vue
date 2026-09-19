<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe0g7_blf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xe0g7_blf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:gps" /></template>
