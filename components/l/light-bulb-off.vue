<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubh0g-bri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubh0g-bri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:light-bulb-off" /></template>
