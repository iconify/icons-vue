<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbn8ei03i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbn8ei03i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:bubble-outcome" /></template>
