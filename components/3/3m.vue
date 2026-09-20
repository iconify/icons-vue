<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oevl31bth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oevl31bth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:3m" /></template>
