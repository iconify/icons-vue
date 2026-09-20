<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omh6_pbct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omh6_pbct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:home-assistant" /></template>
