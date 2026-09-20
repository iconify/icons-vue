<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwvtv4vld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwvtv4vld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:indie-hackers" /></template>
