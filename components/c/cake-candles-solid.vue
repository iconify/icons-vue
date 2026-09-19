<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-_2_25ob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-_2_25ob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:cake-candles-solid" /></template>
